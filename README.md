# 2
calc
<html>
	<head>
		<title>Калькулятор</title>
	</head>
	<body>
		<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
		<div class="container">
			<form name="calculator">
				<br>
					<input type="textfield" name="ans" value="">
				</br>
				<br>
					<input bgcolor= "# 000001" text= "gold" type="button" value="1" onClick="document.calculator.ans.value+='1'">
					<input type="button" value="2" onClick="document.calculator.ans.value+='2'">
					<input type="button" value="3" onClick="document.calculator.ans.value+='3'">
					<input type="button" value="+" onClick="document.calculator.ans.value+='+'">
				</br>
				<br>
					<input type="button" value="4" onClick="document.calculator.ans.value+='4'">
					<input type="button" value="5" onClick="document.calculator.ans.value+='5'">
					<input type="button" value="6" onClick="document.calculator.ans.value+='6'">
					<input type="button" value="-" onClick="document.calculator.ans.value+='-'">
				</br>
				<br>
					<input type="button" value="7" onClick="document.calculator.ans.value+='7'">
					<input type="button" value="8" onClick="document.calculator.ans.value+='8'">
					<input type="button" value="9" onClick="document.calculator.ans.value+='9'">
					<input type="button" value="*" onClick="document.calculator.ans.value+='*'">
				</br>
				<br>
					<input type="button" value="0" onClick="document.calculator.ans.value+='0'">
					<input type="reset" value="С">
					<input type="button" value="=" onClick="document.calculator.ans.value=eval(document.calculator.ans.value)">
					<input type="button" value="/" onClick="document.calculator.ans.value+='/'">
				</br>
				
			</form>
		</div>
		<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous">
		</script>
		<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous">
		</script>
		<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous">
		</script>
	</body>
</html>
