# サッカー情報管理システム
## プロジェクトの概要
このシステムでは、<br>以下の内容を管理します。
- チームリスト
    1. Jリーグ
    1. 欧州リーグ
- 選手リスト
- 試合結果

## ページ構成
| URL | 内容 | サーブレット | JSP |
|---:|:---:|:---|---|
| /home | ホーム | HomeServlet | index.jsp |
| /list | チーム紹介 | TeamServlet | list.jsp |
| /login | ログイン | LoginServlet | login.jsp |

### domainクラスの例
```java
@Data
public class Team {
    private Integer id;
    private String name;
}
```