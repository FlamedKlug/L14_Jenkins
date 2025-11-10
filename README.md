# Демонстрационный проект автотестов UI на основе сайта https://www.ixbt.com/  
## В проекте демонстрируются UI автотесты написанные с применением разметки allure, использованием принципов ООП, интеграцией с Jenkins и TestOps
В проекте проверяется:
- Корректное отображение кук-информера
- Закрытие кук-информера и его скрытие после закрытия
- Видимость иконки поиска
- Видимость иконки Youtube
- Переход в раздел новостей и корректность заголовка в нем

## Продемонстрирован пример создания инфраструктуры проекта: 
- Создан [билд в jenkins](https://jenkins.autotests.cloud/job/C22_Giv_vik_IXBT_full_project/)
![image](https://github.com/TukinAlexey/qa_guru_python_hw_14_full_project-/blob/main/files/Jenkins_1.png)
- К прогонам в Jenkins добавляется [allure отчет](https://jenkins.autotests.cloud/job/C22_Giv_vik_IXBT_full_project/2/allure/#suites) к которому приложены:
  - Скриншот
  - Логи браузера
  - Ресурс страницы
  - Видео прохождение теста 
![image](https://github.com/TukinAlexey/qa_guru_python_hw_14_full_project-/blob/main/files/Allure_1.png)
- Кейсы из прогона добавляются в [TestOps](https://allure.autotests.cloud/project/4825/test-cases/38830?treeId=9437)
![image](https://github.com/TukinAlexey/qa_guru_python_hw_14_full_project-/blob/main/files/TestOps_1.png)
- Настроен запуск автотестов из TestOps
- После прогона в телеграм отправляется отчет о прохождении тестов
![image](https://github.com/FlamedKlug/L14_Jenkins/blob/main/Screenshots/tg_report.jpg)
