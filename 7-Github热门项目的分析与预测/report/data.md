|              | # nodes | # connections |
| :----------: | ------- | ------------- |
|    Watch     | 273854  | 52284333      |
|     Fork     | 145922  | 9998595       |
| IssueComment | 75728   | 746445        |
| PullRequest  | 82538   | 1858879       |

Watch

| Project ID | Project Name | Degree |
| ---------- | ------------ | ------ |
| 25315643   |              | 75802  |
| 19415064   |              | 66787  |
| 11829145   |              | 58203  |
| 18405734   |              | 53952  |
| 43279131   |              | 50303  |
| 44218803   |              | 49621  |
| 42956467   |              | 48866  |
| 41766002   |              | 46044  |
| 41673581   |              | 44284  |
| 42751014   |              | 44088  |



| Project ID | Project Name | Pagerank*10K       |
| ---------- | ------------ | ------------------ |
| 298358641  |              | 8.361969146123766  |
| 105825987  |              | 4.984936069838924  |
| 299547592  |              | 4.979766379553058  |
| 302575005  |              | 4.7750136106390695 |
| 158688580  |              | 4.5270385670842455 |
| 411555862  |              | 4.236097877888353  |
| 262236251  |              | 3.8280171923019966 |
| 412379159  |              | 3.821642626186294  |
| 152188932  |              | 3.517434569992938  |
| 411588174  |              | 3.2551350321033263 |



![image-20220503130301172](/Users/mingli/Library/Application Support/typora-user-images/image-20220503130301172.png)



Fork

| Project ID | Project Name | Degree |
| ---------- | ------------ | ------ |
| 42751014   |              | 7212   |
| 27193779   |              | 6200   |
| 25315643   |              | 6180   |
| 943149     |              | 5936   |
| 13021798   |              | 5927   |
| 501326     |              | 5681   |
| 11167738   |              | 5461   |
| 42050752   |              | 5335   |
| 42586612   |              | 5204   |
| 41766002   |              | 5199   |



| Project ID | Project Name | Pagerank*10K       |
| ---------- | ------------ | ------------------ |
| 1300192    |              | 4.592658112286747  |
| 19415064   |              | 4.326396609246912  |
| 28167802   |              | 4.080367718222198  |
| 2126244    |              | 3.148398384548801  |
| 25315643   |              | 3.1064025527918755 |
| 42586612   |              | 2.7336885130704798 |
| 10270250   |              | 2.617810970175908  |
| 21737465   |              | 2.600708497128455  |
| 41766002   |              | 2.5153832941780627 |
| 18405734   |              | 2.506695593611317  |



![image-20220503131501725](/Users/mingli/Library/Application Support/typora-user-images/image-20220503131501725.png)



pullrequest

| Project ID | Project Name | Degree |
| ---------- | ------------ | ------ |
| 43080782   |              | 2140   |
| 34681440   |              | 2138   |
| 15905207   |              | 1824   |
| 17779381   |              | 1818   |
| 39784415   |              | 1545   |
| 34230966   |              | 1373   |
| 37717474   |              | 1314   |
| 31243958   |              | 1278   |
| 3955647    |              | 1275   |
| 958314     |              | 1273   |



| Project ID | Project Name | Pagerank*10K       |
| ---------- | ------------ | ------------------ |
| 206084     |              | 7.905170272333203  |
| 10974951   |              | 7.497058151336389  |
| 3623050    |              | 3.042879535028293  |
| 8514       |              | 2.983342143858018  |
| 1300192    |              | 2.9291742744834988 |
| 724712     |              | 2.7785296401679123 |
| 7691631    |              | 2.7650817646704735 |
| 6106340    |              | 2.6702894396464067 |
| 6093316    |              | 2.590064697231148  |
| 458058     |              | 2.3487211998781805 |



![image-20220503132137324](/Users/mingli/Library/Application Support/typora-user-images/image-20220503132137324.png)



Issuecomment

| Project ID | Project Name | Degree |
| ---------- | ------------ | ------ |
| 321278     |              | 2306   |
| 27193779   |              | 1808   |
| 206084     |              | 1738   |
| 7691631    |              | 1698   |
| 3228505    |              | 1551   |
| 10270250   |              | 1390   |
| 11061773   |              | 1317   |
| 1420493    |              | 1255   |
| 24560307   |              | 1139   |
| 9384267    |              | 1108   |



| Project ID | Project Name | Pagerank*10K       |
| ---------- | ------------ | ------------------ |
| 321278     |              | 12.836063163558814 |
| 206084     |              | 12.182129136487386 |
| 7691631    |              | 11.334998174029815 |
| 3228505    |              | 9.581670921929092  |
| 27193779   |              | 9.34194119126938   |
| 1420493    |              | 8.09320255471226   |
| 10270250   |              | 7.689296222718188  |
| 11061773   |              | 6.591542444737357  |
| 19872456   |              | 6.071249344805698  |
| 9384267    |              | 5.9682403291913655 |

![image-20220503132451468](/Users/mingli/Library/Application Support/typora-user-images/image-20220503132451468.png)



Cosine similarity
10000
Pagerank

|                          | ForkEvent | IssueCommentEvent | PullRequestEvent | WatchEvent |
| ------------------------ | --------- | ----------------- | ---------------- | ---------- |
| **ForkEvent**            | 1         | 0.22              | 0.32             | 0.49       |
| **IssueCommentEvent**    | 0.22      | 1                 | 0.35             | 0.11       |
| **PullRequestEvent**     | 0.32      | 0.35              | 1                | 0.44       |
| **WatchEvent**           | 0.49      | 0.11              | 0.44             | 1          |
| **Mean**(excluding self) | 0.34      | 0.23              | 0.37             | 0.35       |




10000
Degree

|                       | ForkEvent | IssueCommentEvent | PullRequestEvent | WatchEvent |
| --------------------- | --------- | ----------------- | ---------------- | ---------- |
| **ForkEvent**         | 1         | 0.08              | 0.72             | 0.14       |
| **IssueCommentEvent** | 0.08      | 1                 | 0.04             | 0.10       |
| **PullRequestEvent**  | 0.72      | 0.04              | 1                | 0.22       |
| **WatchEvent**        | 0.14      | 0.10              | 0.22             | 1          |
| Mean(excluding self)  | 0.31      | 0.07              | 0.33             | 0.15       |

