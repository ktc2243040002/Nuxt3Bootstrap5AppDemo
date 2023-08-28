<template>
  <div class="container">
    <div style="background-color: #EEEEEE;">

    <div class="row">
      <div class="col-2">
    <div class="card">
      <div class="card-header">各種入力</div>
      <div class="card-body">
        <p class="card-text"></p>

        <ul class="list-group">
          <li class="list-group-item"><NuxtLink to="/recipe">複合仕訳入力</NuxtLink></li>
          <li class="list-group-item">元帳入力</li>
          <li class="list-group-item">通帳入力</li>
        </ul> 
      </div>
      </div>
    </div>

      <div class="col-10">
        <div class="card">
        <div class="card-header">各種出力</div>
        <div class="card-body">
          <p class="card-text"></p>

        <ul class="list-group list-group-horizontal">
          <li class="list-group-item">仕訳帳</li>
          <li class="list-group-item">出納帳</li>
          <li class="list-group-item">仕訳検索</li>
        </ul>
        <ul class="list-group list-group-horizontal-sm">
          <li class="list-group-item">合計残高試算表</li>
          <li class="list-group-item">補助科目合計残高表</li>
          <li class="list-group-item">消費税課税区分別集計表</li>
        </ul>
        <ul class="list-group list-group-horizontal-md">
          <li class="list-group-item">総勘定元帳</li>
          <li class="list-group-item">補助元帳</li>
          <li class="list-group-item">月次比較財務諸表</li>
        </ul>
        <ul class="list-group list-group-horizontal-lg">
          <li class="list-group-item">個人出納表</li>
          <li class="list-group-item">経費精算申請</li>
          <li class="list-group-item">経費精算承認</li>
        </ul>
        </div>
        </div>
      
        </div>
        </div>
    </div>
  </div>
</template>