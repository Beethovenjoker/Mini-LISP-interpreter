Step1:
在CMD下與程式碼所在的資料夾輸入以下三個指令:

flex FinalProject.l

bison -dy FinalProjecty.y

gcc lex.yy.c y.tab.c


Step2:
在CMD下與程式碼所在的資料夾輸入以下指令來檢查測資:
a.out < 01_1.lsp
(01_1是測資的檔案名)