--------[Mon Feb  3 08:41:28 EST 2020]--------

0.  [big data analysis with scala spark](https://www.coursera.org/learn/scala-spark-big-data/home/welcome)  
1.  installed java, sbt [[link](https://www.coursera.org/learn/scala-spark-big-data/supplement/PH9r4/tools-setup)]  
2.  ```$ sbt```  
	 - it created 2 folders, 'project' and 'project/target'  
	 - ./hello/src/main/scala/example/Hello.scala had the code  
3.  ```$ sbt new sbt/scala-seed.g8 ```  
	 - it will ask for project name 									# entered 'hello'  
	 - it created 2 folders, 'hello' and 'src' folder   
4.  ```$ cd hello  
	   $ sbt  
	   	> compile  
	   	> run
	   	```  
  
--------[Tue Feb  4 07:45:56 EST 2020]--------  
  
0.  reading [this](https://www.scala-sbt.org/release/docs/Setup.html)    
1.  created this git repo to log my learning  
2.  reading [this](https://www.coursera.org/learn/scala-spark-big-data/supplement/817lQ/sbt-tutorial)  

--------[Fri Feb  7 09:06:00 EST 2020]--------

0.  Download the assignment. (link)[https://www.coursera.org/learn/scala-spark-big-data/programming/I6L8m/example]
1.  implement sum and max function
2.  use sbt, console to check the implementation as follows 
	```bash
	(base) Channas-MacBook-Pro:example channa$ sbt
	sbt:progfun1-example> console
	scala> import example.Lists._
	import example.Lists._

	scala> sum(List(1, 2, 3))
	res0: Int = 6

	scala> max(List(1, 4, 22))
	res1: Int = 22

	```