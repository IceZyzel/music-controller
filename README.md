# music-controller
крч мне лень на англе писать это мьюзик контроллер типо заходишь создаёшь руму с определенными параметрами там генерируется 6тизначный код потом этот код другой чел вводит и заходит к тебе в руму и слушаете музыку через спотифай апи 


### для того чтобы всё работало вам надо зайти на spotify for developers и создать свой дешборд в этом дешборде найдёте client id и secret id эти 2 параметра надо вставить в spotify/credetials и ещё надо две команды прописать чтобы работал фронтенд   а ну и чтобы сервер и фронт запустить надо :
cd ./music_controller | python manage.py runserver

 cd ./music_controller | cd./frontend | npm i webpack webpack-cli --save-dev (один раз прописать)
 cd ./music_controller | cd./frontend | npm run dev
### больше ничего не надо удачи )