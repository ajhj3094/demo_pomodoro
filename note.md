settings 內的 :src="require..."，如果沒有 require 這樣寫就是從 public 抓資料，這樣就是從 src/assets 抓資料。這個情況可以兩種寫法。
:src="require('@/assets/' + data.value)"
src="../assets/yay.mp3"

查詢 props: bootstrap-vue -> component reference -> b-table 

#cell(src)="data"