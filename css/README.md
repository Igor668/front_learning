# CSS
> 美化網頁，改變html element default style

* use CSS on HTML  
  * 1.行內樣式(Inline Style)
    * 位置寫在<開始標籤>內的style屬性
      ```sh
      <開始標籤 style="css_name:css_value">內容</結束標籤>
      ```
    * 可同時給予多組CSS 屬性，用 ; 隔開
      ```sh
      style="css_name:css_value; css_name:css_value"
      ```
  * 2.內部樣式(Internal Style Sheet)
    * 撰寫位置在`<head>` 中的`<style>`內
    * 將HTML和CSS分開寫，易管理和維護
    * CSS 語法
      ```sh
      <head>
        <style>
          /* 註解 */
          選擇器 {
            CSS_name:CSS_value;
          }
        <style>
      </head>
      ```
    * 常用選擇器
      1. 標籤選擇器-Type Selector
      2. 類別選擇器-Class Selector
      3. ID選擇器-ID Selector
      4. 通用選擇器-Universal Selector
    * 更多選擇器  
      http://www.w3.org/TR/selectors/
  * 3.外掛模式(External Style Sheet)

  ![](./MD_png/css.PNG "")

* Hyperlink select
  * a:link     未瀏覽的超連結
  * a:visited  已瀏覽的超連結
  * a:hover    滑鼠移至超連結上
  * a:active   滑鼠點選的超連結

* 清單符號
![](./MD_png/list-style-type.PNG)

* 方塊模型
![](./MD_png/box.PNG)