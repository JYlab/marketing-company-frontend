<template>


	
<div id="nav_menu">

<img src="../assets/VictoryMarketing.png" id="logo" height="80px" width="140px">

<ul>
<li><a href="#">회사소개</a></li>
<li><a href="#">웹 마케팅</a></li>
<li><a href="#">모바일 마케팅</a></li>
</ul>
</div> 

</template>

<script>



export default {
    name: 'Menu',

    data: () => ({
		items: [
		{ title: 'Click Me' },
		{ title: 'Click Me' },
		{ title: 'Click Me' },
		{ title: 'Click Me 2' },
		],
	}),
  
}
</script>


<style >
#menu_text { font-size: 20px }

#nav_menu {
	padding-top:0px;
}

#nav_menu ul {
list-style-type:none;
/* 좌측 여백 없애기 */
padding-left:0px;
padding-right:200px;
padding-top:30px;
padding-bottom:50px;
/* 우측 정렬 하기 */
float:right;

}

#nav_menu ul li {
display:inline;
border-left: 1px solid #c0c0c0;
/* 테두리와 메뉴 간격 벌리기. padding: 위 오른쪽 아래 왼쪽; */
padding: 0px 20px 0px 20px;
/* 메뉴와 테두리 사이 간격 벌리기. margin: 위 오른쪽 아래 왼쪽; */
margin: 5px 0px 5px 0px;
font-size:17pt;

}
#nav_menu #logo{
	/* 좌측 여백 없애기 */
padding-left:50px;
/* padding-top:20px; */
/* padding-bottom:20px; */
/* 우측 정렬 하기 */
float:left;
	
}
#nav_menu ul li:first-child {
/* li의 첫번째 요소의 좌측에는 테두리 없애기 */
border-left: none;
}

#nav_menu a {
 text-decoration:none;
 color:#000000
}

#nav_menu a:hover {
 color:#5F5F5F;

 border-bottom:1px solid #5F5F5F;
}

</style>
