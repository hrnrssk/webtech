<html>
  <head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
  </head>
  <body>
    <h1>WEB技術シリーズの課題</h1>
    <% require 'pg' %>
    <% connection = PG::connect(dbname: "goya") %>
    <% connection.internal_encoding = "UTF-8" %>

    <% result = connection.exec("select* from crops WHERE give_for != '自家消費';") %>
    <% data = [] %>
    <% result.each do |record| %>
      <%  data << "ゴーヤの大きさ：#{record["weight"]}　売った相手：#{record["give_for"]}" %>
    <% end %>
    <form action="notjika.cgi" method="POST">
       下記のボタンを押すと、自家消費ではないものの情報ページに飛びます<br><br>
       <!-- valueには、送りたいデータを代入する -->
       <!-- name="goya"を、情報の目印とする -->
      <input type="text" name="notjika" value="<%= data.join(' ') %>">
      <input type="submit" name="送信" >
    </form>
    <% result2 = connection.exec("select* from crops WHERE quality = 'f';") %>
    <% data2 = [] %>
    <% result2.each do |record| %>
      <%  data2 << "ゴーヤの大きさ：#{record["weight"]}　品質：#{record["quality"]}" %>
    <% end %>
    <form action="falsething.cgi" method="POST">
       下記のボタンを押すと、品質が悪いものの情報ページに飛びます<br><br>
       <!-- valueには、送りたいデータを代入する -->
       <!-- name="goya"を、情報の目印とする -->
      <input type="text" name="falsething" value="<%= data2.join(' ') %>">
      <input type="submit" name="送信" >
    </form>
  </body>
</html>
