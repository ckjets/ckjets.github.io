【課題】 
* 都道府県別の総人口推移グラフを表示するSPA(Single Page Application)を構築せよ 
https://www.dropbox.com/s/kppssc1p1di91tz/frontend-wireframe.jpg?dl=0 

* 内容 
1. RESAS(地域経済分析システム) APIの「都道府県一覧」からAPIを取得する 
2. APIレスポンスから都道府県一覧のチェックボックスを動的に生成する 
3. 都道府県にチェックを入れると、RESAS APIから選択された都道府県の「人口構成」を取得する 
4. 人口構成APIレスポンスから、X軸:年、Y軸:人口数の折れ線グラフを動的に生成して表示する 

* 制約 
* Reactをベースに、最新版(9/26時点で v16.5.2)でSPAを構築すること 
* 都道府県一覧および総人口情報はRESAS APIのデータを用いること 
* グラフは Highcharts や Rechart.js サードパーティ製のグラフライブラリを用いて描画すること 
* グラフライブラリは任意のものを用いる 
* Google Chrome最新版で正しく動くこと 

* 注意事項 
* RESAS APIの利用登録(無料)を行い、API Keyを発行する必要がある 
* ソースコードはGitで管理し、作成したソースコードはGitHubにアップロードすること 

* 参考 
* RESAS API: https://opendata.resas-portal.go.jp/ 
* RESAS API仕様書: https://opendata.resas-portal.go.jp/docs/api/v1/index.html 
* React.js: https://reactjs.org/ 
* Highcharts: https://www.highcharts.com/ 
* Recharts.js: http://recharts.org/en-US/ 


* 備考 
* Reactではなく、Angular/Vue/RiotなどJavaScriptのフレームワークでも構わないです 
---------------------------------------------------------------
X-API-KEY
API key: GUg7et7BNeHPhCkOMWIMi6ANFd6kCoPzffIOFLwG