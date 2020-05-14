---
permalink: /my_songs/
---

<section id="banner">
	<h2>我的歌曲</h2>
		<ul class="actions vertical">
		<li><a class="button special icon fa-upload big" id="uploadSongBtn" href="{{'/songs/new' | absolute_url}}">Submit new song</a></li>
	</ul>
</section>
<section id="one" class="wrapper style2">
	<div class="container">
		<div id="songList">
			<div id="searchOptions">
			<input class="search" placeholder="Search Song.."/>
			<span class="sort button small" data-sort="name">S按名字排序</span>
			<span class="sort button small" data-sort="author">按作者排序</span>
			<span class="sort button small" data-sort="timestamp">按日期排序</span>
		</div>
			<ul class="list">
			</ul>
			<ul class="pagination"></ul>
			<div id="noSongsText" style="display:none;"><h1 class="text-center"> 你并没有上传歌曲 :( </h1></div>
		</div>
		<!-- List item template -->
		<div style="display:none;">
			<li id="song-item" class="row songItem">
				<p class="id" style="display:none;"></p>
				<div class="col-sm">
					<strong>名字</strong> 	<p class="name"></p>
				</div>
				<div class="col-sm">
					<strong>原曲作者</strong> <p class="original_author"></p>
				</div>
				<div class="col-sm">
					<strong>日期</strong> 	<p class="date timestamp" data-timestamp=""></p>
				</div>
				<div class="col-sm">
					<strong>下载</strong> <p><a class="download icon fa-download"></a></p>
				</div>
                <div class="col-sm">
					<strong>编辑</strong> <p><a class="update icon fa-pencil"></a></p>
				</div>
                <div class="col-sm">
					<strong>删除</strong> <p><a class="delete icon fa-trash" href="javascript:void(0);"></a></p>
				</div>
                <div class="col-sm">
					<strong>状态</strong> <p><a class="status"></a></p>
				</div>
			</li>
		</div>
		<script src="{{ '/assets/js/my_songs.js' | absolute_url}}"></script>
	</div>
</section>