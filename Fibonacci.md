<!DOCTYPE html>
<html>
<head>
	<title></title>
	<script type="text/javascript">
			// 斐波拉契数列
			function fib(arg) {
				var n = 0, 
					a = 0, b = 0, m = 0;
				while (n < arg){
					m = a + b; // 第n项值 = n-1项值 +　n-2项值

                	if (m == 0) m = 1;

                	a = b; 
                	
                	b = m; // 换位, 第n-1项值在下次运算中为 n-2, n变为 n-1 
                	
                	n = n + 1
                	document.write(m + '-');
				}
			}
		fib(10);
	</script>
</head>
<body>

</body>
</html>