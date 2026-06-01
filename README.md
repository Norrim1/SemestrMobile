Автор: Бабенко Данил Викторович ФИТ-231
Тема: Складской учет  
Описание:
Приложение создано для ведения учёта поставок, включающее создание, обновление и приёмку доставки.  
Работа приложения:  
Сначала попадаем на главный экран списка всех заказов.  
<img width="378" height="842" alt="image" src="https://github.com/user-attachments/assets/5c99efb0-a93c-4404-9ad0-b0758ee73180" />
Здесь можно просмотреть весь список, изменить статус заказа при нажатии на кнопку, просмотреть содержимое заказа по кнопке ShowDetails или нажав на карточку заказа  
<img width="180" height="76" alt="image" src="https://github.com/user-attachments/assets/aaefd881-4a33-41f1-b3c0-3a27ef2725b6" />  
<img width="377" height="833" alt="image" src="https://github.com/user-attachments/assets/c9533e03-a991-401b-9f6e-6ecba6853727" />  
При нажатии на кнопку снизу слева указывается новый заказ, с названием, поставщиком и добавляемым содержимым, которое понимается, как отправленные товары  
<img width="383" height="841" alt="image" src="https://github.com/user-attachments/assets/ceda9820-c890-490e-a628-c00d11c55a97" />  
<img width="313" height="317" alt="image" src="https://github.com/user-attachments/assets/495f4c02-7c1b-4123-b56f-20e40b70a5e3" />  
При попытке принять товар, фактически оформляя принятие поставки, пользователя перекинет на окно где нужно будет подтвердить доставленное содержимое  
<img width="372" height="314" alt="image" src="https://github.com/user-attachments/assets/331a4e88-3c22-4308-a69c-163866cbb83d" />
Обязательные требования:  
Архитектура:  
<img width="125" height="85" alt="image" src="https://github.com/user-attachments/assets/4f9597c2-2fb6-4b47-ac4c-192e105db34c" />  
Применение Koin:  
<img width="216" height="77" alt="image" src="https://github.com/user-attachments/assets/d0e087ec-62e6-4308-b7d4-83b6534b2822" />  
<img width="599" height="659" alt="image" src="https://github.com/user-attachments/assets/b1554c39-34a1-4a91-8346-7d73268ba87f" />  
<img width="443" height="417" alt="image" src="https://github.com/user-attachments/assets/d2b1fb77-fd94-40ea-ae5d-09f599ec03b8" />
Фоновый задачи и сервисы(Отправка уведомления о созданных но не отправлленных заказах):  
<img width="510" height="635" alt="image" src="https://github.com/user-attachments/assets/cd3397d1-1e59-4471-8893-25ffad384461" />  
<img width="541" height="864" alt="image" src="https://github.com/user-attachments/assets/2c9d86c2-6de5-4941-8ffa-9da4d3f3fc6c" />  
<img width="490" height="529" alt="image" src="https://github.com/user-attachments/assets/e3c85d4a-89ac-4daa-be89-624777d4ebc1" />
Анимации:  
Плавное изменение карточки заказа при открытии списка товаров  
<img width="457" height="483" alt="image" src="https://github.com/user-attachments/assets/1ff61309-64d1-40d9-9e2b-767654630daf" />
Появление сообщения об ошибке  
<img width="644" height="86" alt="image" src="https://github.com/user-attachments/assets/e0796a57-7ffc-43c1-8d15-c605f5d3c189" />
XML разметка:
Экран принятия заказа:  
<img width="407" height="634" alt="image" src="https://github.com/user-attachments/assets/b392a927-0ff6-459d-88d9-e091c842d264" />  
Gradle:
<img width="578" height="849" alt="image" src="https://github.com/user-attachments/assets/80e13825-e7e7-4c27-92b1-f406767bbfa7" />  
<img width="584" height="303" alt="image" src="https://github.com/user-attachments/assets/d360f3c3-612f-4b89-b5ac-d7c3de0c2321" />  





