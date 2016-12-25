# Enima-Server

---

### ToDo

- DB
  - Tale : title(이야기제목), desc(이야기 설명)
  - Buy_Tale : tale(외래키), user(외래키), buy_date(구매일자), recent_page(최근 열람한 페이지), recent_date(최근 열람한 일자)
  - Page : tale(외래키)
  - Paragraph : page(외래키), content(이야기 문단)
  - Drawing : page(외래키)
  - Drawing_Blob : drawing(외래키), blob(블롭)
  - Food : title(음식 제목)
  - Cooking : food(외래키), user(외래키)
  - Ingredient : title(재료 제목), desc(재료 설명)
  - Ingredient_Blob : ingredient(외래키), blob()
  - Cooking_Order : cooking(외래키), ingredient(외래키), ingredient_order_num(요리 순서 번호)
- REST JSON

### Later
- Authentication
- Additional Calculating
