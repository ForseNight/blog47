<style type="text/css">
	body{
		background-color: #121212;
	}
	.w_font{
		color:#ffffff;
	}
	.block{
		background-color: #ffffff10;
	}
	.big_font{
		font-size: 40px;
	}
	.small_font{
		font-size: 17px;
	}
	.padding{
		padding: 5px;
	}
	.left{
		position: left;
	}
	.right{
		position: right;		
	}
	.center{
		position: right;		
	}
	.bg_color{
		background-color: #12121200;
	}
	.med_font{
		font-size: 20px;
	}
</style>

<body>
	<center>
		<div class="block">
			<div class="w_font big_font block padding">Описание</div>
			<div class="w_font small_font padding">Программа 47 это программа, смысл которой состоит в том чтоб выполнять самый расширенный спектор задач. Самый точный смысл которые был заложен в программу, это "раскрытие потенциала вычеслительной техники".</div>
		</div>
		<br>
		<div class="block">
			<div class="w_font big_font block padding">
				<button class="right big_font bg_color w_font" onclick="minusic()"><<<</button>
				Список возможностей к которым программа стреммится в себе реализовать
				<button class="left big_font bg_color w_font" onclick="plusic()">>>></button>
			</div>
			<div class="center w_font small_font padding data">СУБД для работы с данными в программе 47.</div>
		</div>
		<br>
		<div class="block">
			<div class="w_font big_font block padding">Принципы к которым придерживается программа 47</div>
			<div class="w_font small_font padding data">1. В системе данных программы 47, не должно присутствовать данные с повторяющимся содержимым.<br>2. Задумманый код должен работать независимо от расположения данных.</div>
		</div>
	</center>
</body>

<script type="text/javascript">
	var data = document.querySelector('.data');
	num = 0;	
	maxNum = 2;
	function minusic(){
		num -= 1;
		listtt(num)
	}

	function plusic(){
		num += 1;
		listtt(num);
	}

	function listtt(x){
		if (num == -1){
			num = maxNum;
		}
		if (num == 3){
			num = 0;
		}

		text = "";

		if (num == 0){
			text = "СУБД для работы с данными в программе 47."
		}
		if (num == 1){
			text = "Способность генерации разнообразных данных."
		}
		if (num == 2){
			text = "Способность работы с разнообразными данными."
		}

		data.innerHTML = text;
	}

</script>
