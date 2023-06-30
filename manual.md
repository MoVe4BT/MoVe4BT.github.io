*   [**Introduction**](introduction)

*   [**Manual**](manual)

*   [**Tutorial**](tutorial)

*   [**Case Study**](case study)
# [](#header-1)**Install and Run GrPAT**

Here we give a brief manual for installing and running **GrPAT**. 

We recommend that you use Ubuntu 20.04 with gcc-11 and g++-11.

## [](#header-3)**1.Install and compile BehaviorTreeCPP-3.8X**
```shell
  sudo apt-get install libzmq3-dev libboost-dev
  git clone --branch v3.8 https://github.com/BehaviorTree/BehaviorTree.CPP.git
  cd BehaviorTree.CPP
  mkdir build
  cd build
  cmake ..
  make -j8
  sudo make install
```
## [](#header-#)**2.Install mono tool**

```shell
  sudo apt install mono-complete
```


## [](#header-#)**3.Other dependencies**

```shell
  sudo apt-get install qtbase5-dev libqt5svg5-dev libdw-dev
  sudo apt-get install qtwebengine5-dev qtpositioning5-dev
```

## [](#header-2)**4.Install and run GrPAT**

```shell
   git clone https://github.com/Huangps/GrPat.git
   cd groot
   cd run
   ./Groot
```

## [](#header-2)**5.Test**
After successfully launching GrPAT, click on **Editor** and then click **LoadTree** in the subsequent pop-up window. 
We provide several examples in the 'example' folder, you can randomly choose one and then click the **Verification** button to see if the result pops up.

<div style="display:flex; flex-direction:row;">
  <img src="resources/test.gif" style="width:80%">
</div>

## [](#header-2)**6.Start modeling and verifying your own BehaviorTree now!**
For information on how to model and verify your own BehaviorTrees,
please refer to our [**Tutorial**](tutorial) and paper.

# [](#header-1)**Contacts**

Please feel free to contact us if you have any questions about **GrPAT**.

*   <font color="#0000FF" size="4">Peishan Huang (huang_ps@nudt.edu.cn)</font>

*   <font color="#0000FF" size="4"> Zhenbang Chen (zbchen@nudt.edu.cn)</font>