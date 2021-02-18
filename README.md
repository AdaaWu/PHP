# <code class="ph">PHP</code>幫資料取個對應key名?


## <code class="blue">撰寫風格</code>
- function 參數提示型別
- 自訂參數名稱比較有意義


```typescript
function people(string $name, int $age)
{
  return  [
      'name' => $name,
      'age' => $age
  ];  
};



echo people('香香',18)['name'];
echo people('香香',18)['age'];

// 香香18
```

---
## 總結

- 不務正業的遊戲企劃
- 最愛寫Code :heart: 
- 感恩 :cat: 
    - 如果認同請幫忙按讚:thumbsup:


---
<style>
code.blue {
  color: #3170a7 !important;
}
code.orange {
  color: #F7A004 !important;
}
code.ph{
    color:#FFF !important;
    background:#3170a7;
    border-radius:8px; 
    padding:3px 9px;
    font-size:3em;
}

</style>
