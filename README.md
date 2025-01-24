# langchain4j-chat-sample

Camel Quarkus の langchain4j-chatコンポーネントを使って、生成AIの Chat Model と連携するサンプルです。

## 設定

`application.properties` の

* %dev.quarkus.langchain4j.openai.base-url
* %dev.quarkus.langchain4j.openai.chat-model.model-name
* %dev.quarkus.langchain4j.openai.api-key

に使用したい生成AIの Base URL と API Key、Chat Modelの名称を記入してください。

## 実行

`./mvnw quarkus:dev`　を、ターミナルから実行後、http://localhost:8080 にアクセスしてください