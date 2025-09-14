# -LSTM
Athena Technology社の技術課題
株価をLSTMを用いて予測する。
LSTM を用いた量子回帰（Pinball Loss)

時系列データについて、過去60日のデータから次のデータを予測する

評価指標は、以下である。
点予測（q50）: RMSE, MAE, MAPE, Directional Accuracy（上げ下げ）
区間: PI Coverage（q10–q90 に入る割合）, PI Avg Width（平均幅）
