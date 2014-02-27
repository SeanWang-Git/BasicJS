//2014年2月27日 Chapter 3

/*
 *
 *多行注释
 *
 */

//单行注释

var user = 1 + 2
var user2 = 1 + 2;
//两种写法都对，但有分号的在后期压缩代码时不会出错，可读性好。

if(true)
	//todoSth
if(true){
	//todoSth
}
//两种写法都对,下面一种更为友好。

function Test(){
	user3 = 1+2;
}
alert(user3);
// user3 在函数内未使用var声明输入全局变量，不提倡使用。
// 严格模式下作用域会出错。
function Test(){
	var user4 = 1+2;
}
alert(user4);
// user4 在函数内声明属于局部变量，作用域在函数体内。

var message = "hi",found = false, age =29;

var message = "hi",
	found = false,
	age = 29;
//不同数据类型对象可以在一句中声明，但换行可读性跟好。

//Javascript中有5种数据类型,4种基本数据类型(undefined、null、Boolean、string)，一种复杂数据类型object。

typeof(message)
// "undefined" --- 如果这个值未定义
// "boolean" --- 如果这个值是布尔值
// "string" --- 如果这个值是字符串
// "number" --- 如果这个值是数值
// "object" --- 这个值是对象或者是null
// "function" --- 这个值是函数

/**undefined**/

var message;
alert(message == undefined) //true

var message = undefined
alert(message == undefined) //true

var message;
alert(message); //undefined
alert(message_error); //error 
//初始化未使用是undefined，未初始化error

var message;
alert(typeof(message));// undefined
alert(typeof(message_error)); // undefined
// 在使用对象时声明是非常重要的，这样我们就清楚的知道对象是未声明还是未初始化

/**null**/

var car = null;
alert(typeof(car)); //object
// null代表空对象指针

if(car !=null){
}
//如果car是一个对象而非其他类型，最好声明为null，这样我们就可以判断对象内存储的是否是对象

alert(null == undefined);// true
// undefined 不要求声明,但是如果变量是保存对象最好声明为null

/**Boolean**/

var found = true;
var lost = false;
//Boolean 区分大小写

Boolean("非空字符串");//String true
Boolean("");//String false

Boolean(11);// Number true
Boolean(0);// Number fasle
Boolean(NaN);// Number false

var test={'a':0,'b':1};
Boolean(test)//Object true
Boolean(null)//Object false

var message ='Hello world'
if(message){
	alert('true');
}

/**Number**/

var objectNum1 = 020; //8进制16
var objectNum2 = 079; //9超过8进制，前一位0作废
var objectNum3 = 080; //8超过8进制，前一位0作废

var objectNum4 = 0xA; //十六进制10 
var objectNum5 = 0x1f;//十六进制31

var objectNum6 = 312e3;//312000 科学计数法
var objectNum7 = 3.0; //3
var objectNum8 = .1; //0.1 不推荐
var objectNum9 = 1.; //1 不推荐
alert(0.1+0.2==0.3) //false,浮点型计算精确到小数点后17位

//NaN Not a number
alert(NaN == NaN);//false
isNaN(NaN);//true
isNaN(12);//false
isNaN("Hello");//true
isNaN(false);//false
isNaN('10');//false

Number();
parseInt();
parseFloat();

/**String**/

var value =10;
value.toString();//10进制 10
value.toString(2);//2进制 1010
value.toString(8);//8进制 10
value.toString(16);//16进制 a

  


