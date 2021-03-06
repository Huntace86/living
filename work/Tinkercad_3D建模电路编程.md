# Tinkecad 3D建模电路编程

[官方主页](https://www.tinkercad.com/)

[参考1](http://blog.sina.com.cn/s/blog_182ab8d210102yxre.html)

[参考2](https://github.com/wf225/iABC/blob/master/docs/%E5%B0%91%E5%84%BF%E7%BC%96%E7%A8%8B/tinkercad_codeblocks/index.md)

[Tinkercad使用注册教程](https://www.3dsishu.com/article-174-1.html)


    Tinkecad作为目前Autodesk公司目前主打教育领域的设计软件，
    集成了3D打印建模、机器人编程等多项时下热门的创客内容。
    简易的操作以及丰富的功能大大开拓了使用者的创意空间。
    Tinkercad可以说是学生、创客、设计师都应该学习的设计软件。
    
    
    Tinkercad作为一款易于上手的快速建模软件，受到了越来越多人的青睐，尤其在3D打印设计方面。
    虽然Tinkercad的界面十分简洁但是功能却十分的丰富。
    
    
    
## 1. 建模设计
    Tinkercad的主要功能之一就是三维建模设计。
    它不同于其他的主流建模软件功能繁多复杂，Tinkercad更注重于快速简单的搭建模型，
    通过各种不同的基本体来进行组合，使用者可以快速的构建出自己的设计。
    也正是因为Tinkercad的简单易上手使之更加适合于中小学生和建模初学者。
    目前Tinkercad已经集成了上百个不同的基本体以供使用者进行模型搭建。
    如果这里面没有你需要的，别担心tinkercad提供了图形编辑功能，
    你可以自己在线创建基本体并上传至云服务器。
    
    
## 2. 电路模块
    为了方便广大创客爱好者Tinkercad现已加入电路模块，
    在建模界面可以找到各类当下流行的各种创客用电路元件，
    使用者在建模设计时可以直接套用方便进行安装设计，加速创意的发挥。
![](https://www.3dsishu.com/data/attachment/forum/201808/28/131433s5e5s2bo3li5u344.jpg)
    
    目前Tinkercad里已经包含了如Arduino电路板、伺服电机、LED灯、面包板等各类教学用电子元器件。
    不仅如此，为了方便使用者安装这些元件，还有专门形状的挖洞工具供你使用哦。

[开关电路参考](https://www.3dsishu.com/article-373-1.html)

    今天我们就简单的学习并了解一下电路功能的制作方法及其流程，
    接下来将会讲解一个简单的案列来初步认识下电路相关的功能，
    这个案例需要实现通过一个小开关的操作，点亮和熄灭一盏led灯。
    登录tinkercad官网，登录账号，进入到主界面.

    第一步：需要先创建一个电路的项目文件，点击左侧的电路（circuits），
       再点击创建新的电路（Create new circuits），
       这个时候就会跳转到我们的电路设计页面。

    第二步：在右侧的组件中将我们需要的配件都拖拽到左侧的主页面中。
       1.led灯：选中led灯后，按住鼠标左键将组件拖拽到左侧，选项框中的的设置默认即可，如下图所示：
       2.纽扣电池（coin cell 3v battery）：相同的方法，将组件拖拽到左侧即可.
       3.开关（Pushbutton）
       4.电阻（resistor）电阻值设置为220欧

    第三部：对现有的组件进行接线操作，操作上比较简单，
       我们只需要鼠标左键依次点击需要连接到一起的触点即可，如下图所示：
       接下来我们我们按照上面的方法，依次连好所有的接线即可：

    这个时候我们就可以测试电路是否能够正常工作了，
    现在需要点击一下右上角的开始测试按钮（Strat simulation），
    按钮状态变为暂停测试（Stopsimulation），接下来，
    我们可以使用鼠标左键点击一下开关，如果电路连接无误的情况下，
    led就会亮起一下，长亮的话，我们需要按住鼠标左键，
    这个时候，led灯就会一直亮起，直到我们松开鼠标左键，才会灭掉。      
    可能有的同学会问，我们为什么要连接一个220欧的电阻呢？
    接下来我们去掉电阻，直接连接，看一下会出现什么状况，如下图所示进行接线；

    我们再次进行测试，会发现led灯变亮了，并且旁边会出现一个叹号，
    把鼠标移动到叹号上，会有错误提示，大致意思就是电流过大了，需要降低电流，
    这里就可以增加一个电阻，来调节一下电流，现在大家应该明白为什么需要增加一个电阻了。

    恢复之前的接线方式，并适当的调整下连接线的颜色和线的布局，如下图所示：
  
  
 
## 3. 编程模拟
    不知道大家有没有过因为接线失误而导致电路板被烧坏的经历。
    不过现在有了Tinkercad的电路模拟功能小编就再也没出现过这种情况了。
    Tinkercad不仅可以在建模上实现模拟元件安装现在又新加入了编程功能。
    不同于其他的编程软件，Tinkercad除了可以编程外使用者还可以自由搭建电路并进行程序模拟。
    编程部分是基于时下最流行的Arduino UNO R3的主板。
    



