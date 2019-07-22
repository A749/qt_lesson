-   命名空间  name space
        Phaser    {  } 
        1.  申明领地
            取名字 var MIUI = {}
            MIUI.version = '10.1';
            MIUI.openSystem = function(){ }
            游戏框架最小化入侵我们的window 
            污染命名空间
        2. var Phaser = {} 挂载到window下
           就是作用域 scope
           window => 
        3. es5 类的构造 function(){} 
           若函数名首字母大写，那我们就认为它是一个类 构造函数
           方法 Phaser.Game.prototype.getName  任何的方法
           