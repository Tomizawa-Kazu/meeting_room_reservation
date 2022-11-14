# 会議室予約アプリ(meeting_room_reservation)

## 開発環境
1. Frontend
    - Python (Streamlit)

2. Backend 
    - Python (FastAPI)

3. 追加ライブラリは,`requirements.txt`参照
    - 仮想環境など使わずに作成したため、ローカル環境のバージョンを記載
    - 作成後にまとめたため、漏れ等あれば、インストールお願いします
    
## 起動方法
1. 2つターミナル(PowerShell等)を用意する
2. ターミナルでmeeting_room_reservationのフォルダのパスに移動する
3. 1つ目（Frontend）のターミナルで下記コマンドを実行する
    ```
    cd app
    streamlit run app.py
    ```
4. 2つ目（Backend）のターミナルで下記コマンドを実行する
    ```
    cd app
    uvicorn sql_app.main:app --reload
    ```

## 画面イメージ
- ユーザ登録画面
![ユーザ登録画面](/image/user_image.png)

- 会議室登録画面
![会議室登録画面](/image/room_image.png)

- 予約一覧画面
![予約一覧画面](/image/booking_image.png)
