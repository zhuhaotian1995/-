<template>
<div class="col-md-4">
  <p>请添加评论</p>
  <ul class="list-group">
    <li class="list-group-item">
      <div class="handle">
        <a href="javascript:;">删除</a>
        <p class="user"><span>yyy</span><span>说：</span></p>
        <p class="centence">vue之神</p>
      </div>
    </li>
    <li class="list-group-item">
      <div class="handle">
        <a href="javascript:;">删除</a>
        <p class="user"><span>xxx</span><span>说：</span></p>
        <p class="centence">vue king</p>
      </div>
    </li>
  </ul>

</div>
</template>

<script>
</script>

<style scoped>
.col-md-4 {
  position: absolute;
  right: 200px;
  top: 220px;
}

.handle a {
  width: 40px;
  position: absolute;
  right: 10px;
  top: 1px;
}
</style>
