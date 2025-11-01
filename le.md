<!doctype html>
<html lang="zh-CN">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>筱云餐馆菜单</title>
  <style>
		* {
			margin: 0;
			padding: 0;
			box-sizing: border-box;
			font-family: "微软雅黑", sans-serif;
		}
		body {
			background-color: white;
			padding: 20px;
		}
		h1 {
			text-align: center;
			color: #333;
			margin-bottom: 30px;
		}
		.menu {
			max-width: 1200px;
			margin: 0 auto;
		}
		.category {
			margin-bottom: 40px;
			background-color: white;
			border-radius: 8px;
			padding: 20px;
		}
		.category h2 {
			color: #ff6600;
			border-bottom: 2px solid #e67e22;
			padding-bottom: 10px;
			margin-bottom: 20px;
		}
		.dish-list {
			display: flex;
			flex-wrap: wrap;
			gap: 20px;
		}
		.dish-item {
			flex: 1 1 280px;
			border: 1px solid white;
			border-radius: 4px;
			padding: 15px;
			transition: all 0.3s ease;
		}
		.dish-item:hover {
			transform: translateY(-5px);
		}
		.dish-name {
			font-size: 18px;
			font-weight: bold;
			color: black;
			margin-bottom: 8px;
		}
		.dish-desc {
			color: #666;
			font-size: 14px;
			margin-bottom: 10px;
			line-height: 1.5;
		}
		.dish-price {
			color: orange;
			font-size: 16px;
			font-weight: bold;
		}
	</style>
 </head>
 <body>
  <h1>筱云餐馆菜单</h1>
  <div class="menu">
   <div class="category">
	<h2>前菜</h2>
	<div class="dish-list">
	 <div class="dish-item">
	  <div class="dish-name">拌黄瓜</div>
	  <div class="dish-desc">清脆爽口，酸辣开胃，精选新鲜黄瓜制作，超级爽吃。</div>
	  <div class="dish-price">¥12</div>
	 </div>
	 <div class="dish-item">
	  <div class="dish-name">鱿鱼粉</div>
	  <div class="dish-desc">酸辣鲜香，超级爽口，走过路过不可错过。</div>
	  <div class="dish-price">¥15</div>
	 </div>
	</div>
   </div>
   <div class="category">
	<h2>主菜</h2>
	<div class="dish-list">
	 <div class="dish-item">
	  <div class="dish-name">红烧肉</div>
	  <div class="dish-desc">肥而不腻，入口即化，五花肉慢炖而成。</div>
	  <div class="dish-price">¥32</div>
	 </div>
	 <div class="dish-item">
	  <div class="dish-name">小炒肉</div>
	  <div class="dish-desc">肉丝嫩滑，经典家常口味，店长强推。</div>
	  <div class="dish-price">¥27</div>
	 </div>
	</div>
   </div>
   <div class="category">
	<h2>甜点</h2>
	<div class="dish-list">
	 <div class="dish-item">
	  <div class="dish-name">芒果布丁</div>
	  <div class="dish-desc">口感丝滑，芒果味浓郁，餐后解腻佳品。</div>
	  <div class="dish-price">¥6</div>
	 </div>
	 <div class="dish-item">
	  <div class="dish-name">泡芙</div>
	  <div class="dish-desc">香甜软糯，奶油绵密，传统西式甜点，喜欢吃甜的可以尝试。</div>
	  <div class="dish-price">¥9</div>
	 </div>
	</div>
   </div>
  </div>
 </body>
</html>