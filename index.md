<!doctype html>
<html>
	<head>
		<title>Kookly</title>
		<meta name="viewport" content="width=device-width, user-scalable=no">
		<style>
			body {
				font-family: sans-serif;
				margin: 0;
				background: #f1f1f1;
			}
			#opnum {
				position: fixed;
				top: 0;
				width: 100%;
			}
			.topbtn {
				color: #252525;
				font-size: 15px;
				width: 50%;
				border: none;
				background: #f1f1f1;
				border-bottom: solid;
				border-bottom-width: 7px;
				border-bottom-color: #a1a1a1;
			}
			#counfo {
				margin-top: 60px;
			}
		</style>
	</head>
	<body>
		<div id="seport">
			<div id="opnum">
				<button class="topbtn" style="color: #ff6e00; font-weight: bold; border-bottom-color: #ff6e00; background: #ffffff;">単品検索</button><button class="topbtn">フルコース検索</button>
			</div>
			<select id="counfo">
				<option value="you">和食</option>
				<option value="wa">洋食</option>
			</select>
		</div>
		<div id="uib"></div>
	</body>
</html>
