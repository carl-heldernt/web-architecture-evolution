# 04 · AngularJS（資料導向 UI）

## 架構

```mermaid
flowchart TB
    Model["Model (JS)"] --> View["View (HTML)"]
    View -->|Two-way Binding| Model
```

## Todo 範例

```html
<input ng-model="newTodo">
<button ng-click="add()">Add</button>

<ul>
  <li ng-repeat="t in todos">{{ t }}</li>
</ul>
```

```js
$scope.todos = [];

$scope.add = function () {
  $scope.todos.push($scope.newTodo);
};
```

## 重點
- 只操作資料
- 畫面自動更新