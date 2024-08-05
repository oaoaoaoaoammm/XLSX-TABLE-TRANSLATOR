# XLSX TABLE TRANSLATOR
Since I work with China, I ran into such a problem that the application does not supply auto-translations, so I wrote a script that does this. You can use other languages

## How to use?
1. download [```main.py```](https://github.com/oaoaoaoaoammm/XLSX-TABLE-TRANSLATOR/blob/main/main.py) and [```requirements.txt```](https://github.com/oaoaoaoaoammm/XLSX-TABLE-TRANSLATOR/blob/main/requirements.txt)
2. in [```main.py```](https://github.com/oaoaoaoaoammm/XLSX-TABLE-TRANSLATOR/blob/main/main.py) change path to table [```file_path = 'table_cn.xlsx'```](https://github.com/oaoaoaoaoammm/XLSX-TABLE-TRANSLATOR/blob/2ae422ffc3142ab586af4ff9b54699a446f6577f/main.py#L8)
3. change sheet name in table [```sheet_name = 'TDSheet Chinese'```](https://github.com/oaoaoaoaoammm/XLSX-TABLE-TRANSLATOR/blob/2ae422ffc3142ab586af4ff9b54699a446f6577f/main.py#L10)
4. and add output file name [```output_file_path = 'table_cn2.xlsx'```](https://github.com/oaoaoaoaoammm/XLSX-TABLE-TRANSLATOR/blob/2ae422ffc3142ab586af4ff9b54699a446f6577f/main.py#L12)
5. if you want to change language, go here:
   [```def translate_text(text, src='ru', dest='zh-cn'):```](https://github.com/oaoaoaoaoammm/XLSX-TABLE-TRANSLATOR/blob/2ae422ffc3142ab586af4ff9b54699a446f6577f/main.py#L21)
   and change ```dest='zh-cn'```
7. launch ```main.py``` and text will be translated and saved in new table


   
# ISSUES
Please, open issues with bugs, let's improve this code together
