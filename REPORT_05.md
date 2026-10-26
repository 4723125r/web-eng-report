# 第5回 Webエンジニアリング演習 レポート
## 学籍番号
4723125
## TODO配列のコード
const todos = [
{ id: 1, title: "型を復習する", completed: true },
{ id: 2, title: "配列を学ぶ", completed: false },
{ id: 3, title: "レポートを書く", completed: false },
{ id: 4, title: "提出する", compleated: false },
];
## TODOを更新した条件
for (const todo of todos) {
  if (todo.id === 2) {
    todo.completed = true;
    console.log(`更新後: ${todo.title} [完了]`);
  }
}

for (const todo of todos) {
  if (todo.id === 3) {
    todo.completed = true;
    console.log(`更新後: ${todo.title} [完了]`);
  }
## 完了件数の更新前後の実行結果
console.log(`完了件数: 更新前 ${completedBefore}件 -> 更新後 ${completedAfter}件`);
