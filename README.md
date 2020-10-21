# studyMD
## prov-tool-prototype

Prototype for the next-generation provisioning tool in Node.js
- とりあえずprojectをuploadしておきます。以下のproto前のmoduleテスト用jsファイルも含まれています。これらはいずれ削除する予定です。
    - activedirectory2test.js
    - index-testdb.js
    - sequelize-test.js

10/6 上記ファイルを削除しました。

## 使い方

(anaconda3-5.2.0) freedom-mac:work2 $ ./boxinput-proto                           
Usage: boxinputtools [options] [command]

Options:   
	-V, --version       output the version number   
	-h, --help          display help for command  

Commands:  
	fromLDAP [options]  Gets user and group information from AD and creates tables and records in the specified database 
	fromCSV [options]   Gets user and group information from CSV and creates tables and records in the specified database 
	help [command]      display help for command

(anaconda3-5.2.0) freedom-mac:work2 $ ./boxinput-proto help fromLDAP
Usage: boxinputtools fromLDAP [options]    

Gets user and group information from AD and creates tables and records in the specified database

Options:    
	-d, --db <flag>        select db package sqlite or postgresql. default is sqlite.    
	-l, --loglevel <flag>  log level. default is info    
	-h, --help             display help for command    
  
(anaconda3-5.2.0) freedom-mac:work2 $ ./boxinput-proto help fromCSV 
Usage: boxinputtools fromCSV [options]    

Gets user and group information from CSV and creates tables and records in the specified database   

Options:    
	-d, --db <flag>        select db package sqlite or postgresql. default is sqlite.    
	  -l, --loglevel <flag>  log level. default is info    
	  -h, --help             display help for command   
