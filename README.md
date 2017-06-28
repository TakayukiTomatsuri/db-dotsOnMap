# README

自転車の走行状態を調査する自作アプリのバックエンド(の一部)になります。  

位置情報と時刻やその時点の速度やタイプ(例えば、横に避ける：DODGE、急ブレーキ：SUDDEN-BRAKINGなど)などを記録するデータベースを操作するためのAPIを提供する、Ruby on Railsを使ったWebアプリです。  
  
  
http://(ドメイン名)/api/search/rectangle/json/?lat1=36.6789&long1=146.78894&lat2=36.6489&long2=146.79894  
とかやるとクエリに沿ったデータベースの内容をJSON形式で返してくれます。  
  
取得したログをPOSTするときもJSON形式です。  

