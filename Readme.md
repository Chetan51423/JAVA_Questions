👉 Que:1 What are java APPlets? <br>
-> they are small specialize application in java to be embedded within web browsers
-> They were a key components in early web development and were created using java Applets API
-> Howeveer in modern web development we do not use java Applets
-> It is decline due to the security issues and advent of alternative technologies  like javascript.

# key features

1) Embeded in web pages
2) platform Independence
3) security model -> they were run in a restricted environment known as "sandbox" to prevent to access from user side
4) java applet lifecycle  --> init(), start(), stop(), destroy()
5) deprecated -> they are deprecated from java 9
----------------------------------------------------------------------------------------------------------

👉 Que:2 Why we should not use static variable insdie any method as local variable ?

-> static variable are associate with the class
-> they are initialized only once
-> when the class is loaded they are initialized
-> and they retain their value throughtout  lifetife of program

-> local variable have limited scope -- static variable have scope in entire class
-> local variable are access only inside the method -- where as static variable throught the class
-> local variable lifetime is short -- where as life time of static variable is till then till the calss is loaded 
-> local variable are initialized everytime when the methods are called -- where as static variable is initialized is only onces and their value is shared among all instances