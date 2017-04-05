&where=`{"Data.old_price:>=": 1}`  // выборка по старой цене, которая больше 1 
&where=`{"Data.new": 1}`          // выборка по опции new, которая равна 1

&innerJoin=`{"Options":{"class":"msProductOption"}}`
&groupby=`msProduct.id`
&where=`{"Options.key":"hot","Options.value:LIKE":"1"}`   //выборка по опции и сравнение ее с 1
