# XML
21. Создать внешний репозиторий c названием XML.

new
create repository

 22. Клонировать репозиторий XML на локальный компьютер.

git clone https://github.com/OlgaNastTest/XML.git

 23. Внутри локального XML создать файл “new.xml”.

cd XML
touch new.xml

 24. Добавить файл под гит.

git add new.xml

 25. Закоммитить файл.

git commit -m "add new.xml"

 26. Отправить файл на внешний GitHub репозиторий.

git push

 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

cat >> new.xml
<?xml version="1.0" encoding="utf-8"?>
<information_about_yourself>
	<full_name> Olga Nastsiushenka</full_name>
	<age>32</age>
	<number_of_pets>0</number_of_pets>
	<future_desired_salary>1000$</future_desired_salary>
</information_about_yourself>

Ctr C

 28. Отправить изменения на внешний репозиторий.

git add new.xml
git commit -m "replace new.xml"
git push

 29. Создать файл preferences.xml

touch preferences.xml

 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

cat >> preferences.xml
<?xml version="1.0" encoding="utf-8"?>
<my_preferences>
		<favorite_movie>1+1</favorite_movie>
		<favorite_series>The Big Bang Theory</favorite_series>
		<favorite_food>Pasta with seafood</favorite_food>
		<favorite_time_of_year>Summer</favorite_time_of_year>
		<country_you_would_like_to_visit>Italy</country_you_would_like_to_visit>
</my_preferences>

 Ctr C

 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

cat > sklls.xml
<?xml version="1.0" encoding="utf-8"?>
<skills>
	<teory>The basics of testing - Types of testing/ SDLC/ STLC/Software development methodologies/ test design techniques</teory>
	<cs>Client-server architecture</cs>
	<doc>Documentation - Checklists / Bug_reports / Test-case / Requirements</doc>
	<lin>Terminal Linux</lin>
	<git>Git,GitHub,GitBush</git>
	<post>Postman</post>
	<s>SQL</s>
	<dev>Chrome_DevTools</dev>
	<mob>Mobile testing</mob>
</skills>

Ctr C
 32. Сделать коммит в одну строку.

git add preferences.xml skills.xml && git commit -m "2 new files"

 33. Отправить сразу 2 файла на внешний репозиторий.

git push

 34. На веб интерфейсе создать файл bug_report.xml.

Create new file
Edit new file: bug_report.xml

 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

Commit new file

 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

<?xml version="1.0" encoding="utf-8"?>
<bug_report_structure>
    <summary>summary</summary>
    <project>project</project>
    <component>component</component>
    <version>version</version>
    <severity>severity</severity>
    <priority>priority</priority>
    <steps_to_reproduce>steps to reproduce</steps_to_reproduce>
    <actual_result>actual result</actual_result>
    <expected_result>expected result</expected_result>
    <additional_information>additional information</additional_information>
</bug_report_structure>

 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

Commit changes

 38. Синхронизировать внешний и локальный репозиторий XML

git pull
