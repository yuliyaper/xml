# XML
    Создать внешний репозиторий c названием XML           Create a new repository

 
    Клонировать репозиторий XML на локальный компьютер     $ git clone git@github.com:yuliyaper/JSON.git
    Внутри локального XML создать файл “new.xml”           $ touch new.xml
    Добавить файл под гит                                  $ git add .
    Закоммитить файл.                                      $ git commit -m "new file xml"
    Отправить файл на внешний GitHub репозиторий.          $ git push
 
    Отредактировать содержание файла “new.xml” -            $vim new. xml
    написать информацию о себе                               нажать i
    (ФИО, возраст, количество домашних                      <info>
    животных, будущая желаемая зарплата).                   <FIO>Perevoshikova Yuliya Leonidovna</FIO>
    Всё написать в формате xml                              <age>41</age>
                                                            <animal>1</animal>
                                                            <salary>500</salary>
                                                            </info>
		                                            нажать esp : wq
                                        			                                                  
    Отправить изменения на внешний репозиторий.             $ git commit -am "change 1 new_xml"
                                                            $ git push
 
    Создать файл preferences.xml                            $ touch preferences.xml
 
    В файл preferences.xml добавить информацию о            $ vim preferences.xml
    своих предпочтениях (Любимый фильм, любимый сериал,      нажать i
    любимая еда, любимое время года,                        <info>
    стрaна которую хотели бы посетить) в формате JSON.	    <favorite_emovie>Electronics</favorite_movie>
                                                            <favorite_TV_series>Sasha and Tanya</favorite_TV_series>
	                                                    <favorite_food>soup</favorite_food>
	                                                    <favorite_time_of_the_year>winter</favorite_time_of_the_year>
	                                                    <the_country_you_would_like_to_visit>Switze</the_country_you_would_like_to_visit>
                                                            </info>
                                                            нажать esp : wq
  
     Создать файл sklls.xml добавить информацию о            $touch skils.xml
     скиллах которые будут изучены на курсе                  $ vim skils.xml
     в формате xml                                           <info>
	                                                     <studied_skills>basic testing theory,JSON,XML,API,
															                               Posman,DeVTools,Fidler,SQL</studied_skills>
                                                             </info> 
		
    Сделать коммит в одну строку.											 
    Отправить сразу 2 файла на внешний репозиторийmn        $ git add .
                                                            $ git commit -m "2 files"
                                                            $ git push
 
    На веб интерфейсе создать файл bug_report.xml           Add file
                                                            Create new file
							    Commit new file
    Сделать Commit changes (сохранить) изменения            Commit changes
     на веб интерфейсе.
	 
    На веб интерфейсе модифицировать файл bug_report.xml,  Нажать на bug_report.xml
     добавить баг репорт в формате xml.                    Edit this file
     
    Сделать Commit changes (сохранить) изменения на        Commit changes
     веб интерфейсе.                                         
    Синхронизировать внешний и локальный репозиторий xml    $ git pull
