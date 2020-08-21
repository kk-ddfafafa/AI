# AI
こちらは日経平均株価データから売買判断をするAIに関するコードです。  
すべてgoogleColaboratoryで作成しています。  
ProcessData_py.ipynbでは日経平均株価を取得、加工しています。  
deep_rl_trader_STOCK_py.ipynbはlstmを使って売買判断をするコードです。  
DPPO_stock.ipynbはPPOを使って売買判断をするコードです。  


1,ProcessData_py.ipynbについて  
制作目的:日経平均株価のデータを取得し、加工する  
制作時期:不明（一週間もかかっていません）  
使用言語:python  
  
2,deep_rl_trader_STOCK_py.ipynbについて  
制作目的:日経平均株価データを使って強化学習を行い、売買判断をさせる  
制作時期:2019年7月～2019年8月ごろ  
使用言語:python  
使用したライブラリ:keras  
その他特記:lstmを使用して強化学習をしています。lstmを使用した目的は、lstmが時系列データの予測に強いとされるからです。  
  
3,DPPO_stock.ipynbについて  
制作目的:日経平均株価データを取得し、加工する  
制作時期:2019年8月ごろ～2019年9月  
使用言語:python  
使用したライブラリ:tensorflow  
その他特記:PPOを使用して今日学習をしています。PPOを使用した目的は、PPOは実装が簡単であるにもかかわらず高い成績が出ると知ったからです。  
