---
permalink: /dashboard/
---

<section id="banner">
	<h2>控制面板</h2>
</section>
<section id="one" class="wrapper style2">
	<div class="container">
		<div id="songList">
			<div id="searchOptions">
			<input class="search" placeholder="Search Song.."/>
			<span class="sort button small" data-sort="name">按名字排序</span>
			<span class="sort button small" data-sort="author">按作者排序</span>
			<span class="sort button small" data-sort="timestamp">按日期排序</span>
		</div>
			<ul class="list">
			</ul>
			<ul class="pagination"></ul>
		</div>
		<!-- List item template -->
		<div style="display:none;">
			<li id="song-item" class="row songItem">
				<p class="id" style="display:none;"></p>
				<div class="col-sm">
					<strong>名字</strong> 	<p class="name"></p>
				</div>
				<div class="col-sm">
					<strong>作者</strong> <p class="author"></p>
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
					<strong>同意 </strong> <p><a class="accept icon fa-check" href="javascript:void(0);" style="color: green;"></a></p>
				</div>
				<div class="col-sm">
					<strong>拒绝 </strong> <p><a class="deny icon fa-close" href="javascript:void(0);" style="color: red;"></a></p>
				</div>
			</li>
		</div>
		<script src="{{ '/assets/js/dashboard.js' | absolute_url}}"></script>
	</div>
</section>