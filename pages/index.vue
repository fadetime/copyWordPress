<template>
    <div id="home">
		<topbar />
		<div class="home_top">
			<div class="home_top_first">
				<span>HUGE SALE UP TO 80% OFF</span>
			</div>
			<div class="home_top_second">
				<span>DIAL UP THE GLAMOUR IN AN ELEGANT COCKTAIL DRESS</span>
			</div>
			<div class="home_top_third">
				<span>VIEW COLLECTION</span>
			</div>
		</div>
		<div class="home_center">
			<div class="home_center_title">
				<span>LATEST PRODUCTS</span>
			</div>
			<div class="home_center_content">
				<div class="home_center_content_item">
					<div class="home_center_content_item_img">
						<img src="http://40.117.130.57/wp-content/uploads/2019/08/roland-denes-QT94VAhgzsE-unsplash-1-230x230.jpg">
					</div>
					<div class="home_center_content_item_title">
						<span>BLACK DRESS</span>
					</div>
					<div class="home_center_content_item_price">
						<span>$15.00</span>
					</div>
				</div>
				<div class="home_center_content_item">
					<div class="home_center_content_item_img">
						<img src="http://40.117.130.57/wp-content/uploads/2019/08/roland-denes-QT94VAhgzsE-unsplash-1-230x230.jpg">
					</div>
					<div class="home_center_content_item_title">
						<span>BLACK DRESS</span>
					</div>
					<div class="home_center_content_item_price">
						<span>$15.00</span>
					</div>
				</div>
				<div class="home_center_content_item">
					<div class="home_center_content_item_img">
						<img src="http://40.117.130.57/wp-content/uploads/2019/08/roland-denes-QT94VAhgzsE-unsplash-1-230x230.jpg">
					</div>
					<div class="home_center_content_item_title">
						<span>BLACK DRESS</span>
					</div>
					<div class="home_center_content_item_price">
						<span>$15.00</span>
					</div>
				</div>
				<div class="home_center_content_item">
					<div class="home_center_content_item_img">
						<img src="http://40.117.130.57/wp-content/uploads/2019/08/roland-denes-QT94VAhgzsE-unsplash-1-230x230.jpg">
					</div>
					<div class="home_center_content_item_title">
						<span>BLACK DRESS</span>
					</div>
					<div class="home_center_content_item_price">
						<span>$15.00</span>
					</div>
				</div>
			</div>
		</div>
    </div>
</template>

<script>
import topbar from '../components/topBar'

export default {
	components:{
		topbar
	}
};
</script>

<style>
.home_top{
	min-height: 100vh;
	background-image: url(https://s20206.pcdn.co/neve-shop-bb/wp-content/uploads/sites/256/2019/08/nv-shop-slide1.jpg);
    background-repeat: no-repeat;
    background-position: center center;
    background-attachment: fixed;
    background-size: cover;
	color: #fff;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	margin-bottom: 50px;
}
.home_top_first{
	font-size: 48px;
	font-weight: 400;
	letter-spacing: 10px;
	margin-bottom: 20px;
}
.home_top_second{
	letter-spacing: 4px;
	margin: 20px 0;
}
.home_top_third{
	font-size: 12px;
	margin: 20px 0;
	border: 1px solid #fff;
	padding: 8px 40px;
	border-radius: 2px;
	cursor: pointer;
}
.home_center_title{
	text-align: center;
	font-size: 30px;
	letter-spacing: 2px;
	font-weight: 400;
	margin: 20px;
}
.home_center_content{
	display: flex;
	justify-content: space-between;
}
.home_center_content_item_img{
	width: 242px;
	height: 242px;
	margin-bottom: 20px;
}
.home_center_content_item_img img{
	object-fit: cover;
	width: 100%;
	height: 100%;
}
.home_center_content_item_title{
	font-weight: 600;
	text-transform: uppercase;
	padding: 8px 0;
}
.home_center_content_item_price{
	font-weight: 700;
	font-size: 14px;
}
</style>
