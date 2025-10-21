1 原始的定投回测pnl

反映了价格基本的走势👇
<img width="1020" height="544" alt="download" src="https://github.com/user-attachments/assets/e5507dbc-a3c3-4229-9e4b-bac7a5f4cb9c" />


2 通过波动率自相关性 构建交易规则 range[t] = k * range[t-1]

图为 k=0.5 的回测pnl👇
<img width="1013" height="544" alt="download" src="https://github.com/user-attachments/assets/a3e750fa-2720-4f90-8f1b-4fd4749d75ae" />


3 通过扫描k值 从0-1 查看 夏普比 随 k 的变化

表明 k 在某一范围 夏普比 趋于稳定👇
<img width="1189" height="590" alt="download" src="https://github.com/user-attachments/assets/d4655ab7-5784-44cb-98e8-862313b12b17" />

