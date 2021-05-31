## スクレイピングで気象データを取得  
- get_weather.ipynb  
https://qiita.com/OSAKO/items/d25b8484d35ef4fe19e0  

## OpenWeather API で気象データを取得  
- weather_api.ipynb  
アカウントを作成し、仮登録メールから登録処理し、しばらく経つとAPIが使えるようになる。  
https://openweathermap.org/  

下記 xxx に 右上のアカウント名から MyAPI を選択し、Key に記載のAPIキーを weather_api.ipynb のxxxの部分に張り付ける。  
```python
API_KEY = "xxx"
```

### 参考ブログ
風向を示す数値から方角を表示するライブラリ、wxparams を使用しており、インストールが必要。  
- 気象要素を計算するPythonモジュールを公開します  
https://qiita.com/Yoshiki443/items/6a4682bebdf87bd82cff  
- wxparams GitHub  
https://github.com/Yoshiki443/weather_parameters  

```python
!pip install git+https://github.com/Yoshiki443/weather_parameters
```