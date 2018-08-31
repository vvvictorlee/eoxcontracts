# eoxcontracts
基于以太openzeppelin智能合约安全框架
部分合约转换成EOS的智能合约C++版本。
其中
## eoxtoken   
基于StandardToken 实现ERC20 token代币合约 
## eoxpayment
基于pullpayment 等 实现基于第三方支付托管合约
## eoxcrowdsale
基于crowdsale等众筹合约
eos下contracts的CMakelists.txt中加入

	add_subdirectory(eoxtoken)
	add_subdirectory(eoxpayment)
	add_subdirectory(eoxcrowdsale)

contracts下的文件夹加到eos/contracts里  

unittests下的文件加到eos/unittests里  

初步可以编译通过。 

进一步测试还在进行中。。。  

2018.8.31 开学前一天