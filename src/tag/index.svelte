<svelte:head>
	<link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
    />
</svelte:head>
<main>
	<div style="display: flex; flex-direction: row;justify-content: space-around">
		<div class="btn tag-1">
		  Tag
		</div>
		<div class="btn tag-2">
		  Tag
		</div>
		<div class="btn tag-3">
		  Tag
		</div>
		<div class="btn tag-4">
		  Tag
		</div>
		<div class="btn tag-5">
		  Tag
		</div>
		<div class="btn tag-6">
		  Tag
		</div>
		<div class="btn tag-6">
		  Tag<i class="icon-right pointer fa fa-times"></i>
		</div>
  
	</div>
</main>

<style>
	.btn {
        color: black;
        font-weight: bold;
        font-family: Arial;
        background-color: #ffffff;
        border: 1px solid rgb(58, 58, 58);
        padding-right: 25px;
        padding-left: 25px;
        padding-top: 10px;
        padding-bottom: 10px;
        border-radius: 5px;
      }
	  .tag-1{
        font-size: 13px;
        padding-top: 7px;
        padding-bottom: 7px;
        border:none;
        color: #ffffff;
        background-color: #4b83f3;
        cursor: default;
      }
      .tag-2{
        font-size: 13px;
        padding-top: 7px;
        padding-bottom: 7px;
        border:none;
        color: #4b83f3;
        background-color: #c8d5fc;
        cursor: default;
      }
      .tag-3{
        font-size: 13px;
        padding-top: 7px;
        padding-bottom: 7px;
        border:none;
        color: #09f0fc;
        background-color: #e9fdff;
        cursor: default;
      }
      .tag-4{
        font-size: 13px;
        padding-top: 7px;
        padding-bottom: 7px;
        border:none;
        color: #3ef7b6;
        background-color: #e8faf2;
        cursor: default;
      }
      .tag-5{
        font-size: 13px;
        padding-top: 7px;
        padding-bottom: 7px;
        border:none;
        color: #faac36;
        background-color: #fdf4e5;
        cursor: default;
      }
      .tag-6{
        font-size: 13px;
        padding-top: 7px;
        padding-bottom: 7px;
        border:none;
        color: #fd5b68;
        background-color: #fff2f3;
        cursor: default;
      }
      .tag-6{
        font-size: 13px;
        padding-top: 7px;
        padding-bottom: 7px;
        border:none;
        color: #8f91b1;
        background-color: #f5f5fa;
        cursor: default;
      }
      .pointer{
        cursor: pointer;
      }
	  .icon-left {
        margin-right: 5px;
      }
      .icon-right {
        margin-left: 5px;
      }
</style>