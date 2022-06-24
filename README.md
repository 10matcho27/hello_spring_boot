# hello_spring_boot

  - Spring Initializerを使用

## Spring Initializerの設定項目

  - Project: Gradle Project
    - Language: Java
    - Spring Boot: 2.7.1 (SNAPSHOTの書かれていない最新のやつ)
    - Project Metadata:

        |--Group: jp.kobespiral

        |--Artifact: hello

        |--Name: hello

        |--Description: 猫アプリ as 初めてのSpring Boot アプリケーション．

        |--Package name: jp.kobespiral.hello (自動入力される)

        |--Packaging: war

        |--Java: 11 (※2021/06現在、VSCode上だと8,16は動かない！)

    - Dependencies (Ctrlを押しながら操作すると複数同時に選べる) 

        |--Spring Boot DevTools (開発ツール)

        |--Lombok (コンストラクタやsetter/getterを自動生成してくれる神ライブラリ)

        |--Spring Web (Webアプリを作るときは必須)
        
        |--Thymeleaf (HTML テンプレートエンジン)