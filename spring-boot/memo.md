# Spring学習で生まれた疑問

# Spring学習で生まれた疑問

## Beanと依存性注入

1. Spring Beanとは何ですか？通常のJavaオブジェクトと何が違いますか？
2. Springはアプリケーション起動時にBeanをどのように見つけ、管理しますか？
3. コンストラクタインジェクションとは何ですか？Springは依存オブジェクトをどのようにコンストラクタへ渡しますか？
4. コンストラクタ引数にインターフェース型を指定した場合、Springは実装クラスをどのように選びますか？
5. 同じインターフェースを実装するBeanが複数ある場合、どのように選択しますか？
6. `ApplicationContext` や `ApplicationEventPublisher` は何をするもので、Springからどのように提供されますか？

## インターフェースと実装

7. Javaの `interface` と `implements` は何を表しますか？
8. インターフェース型の変数に実装クラスのインスタンスを代入できるのはなぜですか？
9. インターフェース型の変数からメソッドを呼び出すと、実行時にはどの実装が使われますか？
10. 実装クラスを直接参照せず、インターフェースを使う設計にはどのような利点がありますか？

## Spring Security

11. `AuthenticationManager` は何を担当し、どのように認証を実行しますか？
12. `@PreAuthorize` はいつ評価され、`permitAll()` や `isAuthenticated()` は何を意味しますか？
13. メソッド単位の認可設定と、HTTPリクエスト単位のセキュリティ設定はどう関係しますか？

## Javaの基本概念

14. Javaにおける「型」とは何ですか？プリミティブ型、クラス型、recordはどう分類されますか？
15. `new` は何を行い、作られたオブジェクトと変数の型はどう関係しますか？
16. コンストラクタは何をするものですか？recordのコンパクトコンストラクタは通常のコンストラクタとどう違いますか？
17. Javaでは、インターフェース型の変数を通じたメソッド呼び出しで、実装が選ばれる仕組みは何ですか？
18. なぜrecordはコンパクトコンストラクタなのか？

## 処理の流れと永続化

19. Repositoryのインターフェースから、具体的なデータベース処理まで、呼び出しはどのように流れますか？
20. アプリケーションサービス、Repository、DAOはそれぞれどのような責務を担いますか？
21. データベースのトランザクションとは何ですか？複数の書き込みを一括で扱う利点は何ですか？

## 参考資料

- [Spring Framework: Dependency Injection](https://docs.spring.io/spring-framework/reference/core/beans/dependencies/factory-collaborators.html)
- [Spring Framework: Classpath Scanning and Managed Components](https://docs.spring.io/spring-framework/reference/core/beans/classpath-scanning.html)
- [Spring Framework: Application Events and Listeners](https://docs.spring.io/spring-framework/reference/core/beans/context-introduction.html#context-functionality-events)
- [Spring Security: Method Security](https://docs.spring.io/spring-security/reference/servlet/authorization/method-security.html)
- [Java公式チュートリアル：Interfaces](https://docs.oracle.com/javase/tutorial/java/IandI/createinterface.html)