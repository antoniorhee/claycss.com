---
title: Management Bar
description: Components
layout: "guide"
weight: 100
---

{literal}
	<style>
		#wrapper {
			overflow-x: visible;
		}
	</style>
{/literal}

<article id="1">

### Navbar Management Bar

<nav class="navbar navbar-expand">
	<ul class="navbar-nav">
		<li class="nav-item">
			<div class="form-check">
				<label class="form-check-label">
					<input class="form-check-input" type="checkbox" value="">
				</label>
			</div>
		</li>
		<li class="dropdown nav-item">
			<a class="nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-magic">
					<use xlink:href="/vendor/clay/icons.svg#magic" />
				</svg>
			</a>
			<a aria-expanded="false" class="dropdown-toggle nav-link navbar-d-breakpoint-block" data-toggle="dropdown" href="#1" role="button">
				<span class="navbar-text-truncate">Filter and Order</span>
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-caret-bottom">
					<use xlink:href="/vendor/clay/icons.svg#caret-bottom" />
				</svg>
			</a>
			<div class="dropdown-menu" role="menu">
				<a class="dropdown-item" href="#1">Action</a>
				<a class="dropdown-item" href="#1">Another action</a>
				<a class="dropdown-item" href="#1">Something else here</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="#1">Separated link</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="#1">One more separated link</a>
			</div>
		</li>
		<li class="nav-item">
			<a class="nav-link" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-import-export">
					<use xlink:href="/vendor/clay/icons.svg#import-export" />
				</svg>
			</a>
		</li>
	</ul>
	<div class="navbar-form navbar-form-autofit navbar-overlay navbar-overlay-sm-down">
		<form role="search">
			<div class="input-group input-group-inset">
				<div class="input-group-input">
					<input class="form-control" placeholder="Search for..." type="text">
				</div>
				<span class="input-group-inset-item">
					<button class="btn btn-link clay-site-close-overlay-sm-down navbar-d-breakpoint-none" type="button">
						<svg aria-hidden="true" class="lexicon-icon lexicon-icon-times">
							<use xlink:href="/vendor/clay/icons.svg#times" />
						</svg>
					</button>
					<button class="btn btn-link navbar-d-breakpoint-block" type="button">
						<svg aria-hidden="true" class="lexicon-icon lexicon-icon-search">
							<use xlink:href="/vendor/clay/icons.svg#search" />
						</svg>
					</button>
				</span>
			</div>
		</form>
	</div>
	<ul class="navbar-nav">
		<li class="nav-item">
			<a class="clay-site-open-overlay-sm-down nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-search">
					<use xlink:href="/vendor/clay/icons.svg#search" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="nav-link navbar-d-breakpoint-block" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-view">
					<use xlink:href="/vendor/clay/icons.svg#view" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="nav-link navbar-d-breakpoint-block" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-table">
					<use xlink:href="/vendor/clay/icons.svg#table" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="btn btn-secondary nav-btn navbar-d-breakpoint-block" href="#1">Create Dynamic List</a>
			<a class="nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-list">
					<use xlink:href="/vendor/clay/icons.svg#list" />
				</svg>
			</a>
		</li>
	</ul>
</nav>

<nav class="navbar navbar-expand navbar-light navbar-light-bg">
	<ul class="navbar-nav">
		<li class="nav-item">
			<div class="form-check">
				<label class="form-check-label">
					<input class="form-check-input" type="checkbox" value="">
				</label>
			</div>
		</li>
		<li class="dropdown nav-item">
			<a class="nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-magic">
					<use xlink:href="/vendor/clay/icons.svg#magic" />
				</svg>
			</a>
			<a aria-expanded="false" class="dropdown-toggle nav-link navbar-d-breakpoint-block" data-toggle="dropdown" href="#1" role="button">
				<span class="navbar-text-truncate">Filter and Order</span>
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-caret-bottom">
					<use xlink:href="/vendor/clay/icons.svg#caret-bottom" />
				</svg>
			</a>
			<div class="dropdown-menu" role="menu">
				<a class="dropdown-item" href="#1">Action</a>
				<a class="dropdown-item" href="#1">Another action</a>
				<a class="dropdown-item" href="#1">Something else here</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="#1">Separated link</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="#1">One more separated link</a>
			</div>
		</li>
		<li class="nav-item">
			<a class="nav-link" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-import-export">
					<use xlink:href="/vendor/clay/icons.svg#import-export" />
				</svg>
			</a>
		</li>
	</ul>
	<div class="navbar-form navbar-form-autofit navbar-overlay navbar-overlay-sm-down">
		<form role="search">
			<div class="input-group input-group-inset">
				<div class="input-group-input">
					<input class="form-control" placeholder="Search for..." type="text">
				</div>
				<span class="input-group-inset-item">
					<button class="btn btn-link clay-site-close-overlay-sm-down navbar-d-breakpoint-none" type="button">
						<svg aria-hidden="true" class="lexicon-icon lexicon-icon-times">
							<use xlink:href="/vendor/clay/icons.svg#times" />
						</svg>
					</button>
					<button class="btn btn-link navbar-d-breakpoint-block" type="button">
						<svg aria-hidden="true" class="lexicon-icon lexicon-icon-search">
							<use xlink:href="/vendor/clay/icons.svg#search" />
						</svg>
					</button>
				</span>
			</div>
		</form>
	</div>
	<ul class="navbar-nav">
		<li class="nav-item">
			<a class="nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="clay-site-open-overlay-sm-down lexicon-icon lexicon-icon-search">
					<use xlink:href="/vendor/clay/icons.svg#search" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="nav-link navbar-d-breakpoint-block" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-view">
					<use xlink:href="/vendor/clay/icons.svg#view" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="nav-link navbar-d-breakpoint-block" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-table">
					<use xlink:href="/vendor/clay/icons.svg#table" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="btn btn-secondary nav-btn navbar-d-breakpoint-block" href="#1">
				Create Dynamic List
			</a>
			<a class="nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-list">
					<use xlink:href="/vendor/clay/icons.svg#list" />
				</svg>
			</a>
		</li>
	</ul>
</nav>

<nav class="navbar navbar-dark navbar-dark-bg navbar-expand">
	<ul class="navbar-nav">
		<li class="nav-item">
			<div class="form-check">
				<label class="form-check-label">
					<input class="form-check-input" type="checkbox" value="">
				</label>
			</div>
		</li>
		<li class="dropdown nav-item">
			<a class="d-md-none nav-link" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-magic">
					<use xlink:href="/vendor/clay/icons.svg#magic" />
				</svg>
			</a>
			<a aria-expanded="false" class="d-md-inline-block d-none dropdown-toggle nav-link" data-toggle="dropdown" href="#1" role="button">
				<span class="navbar-text-truncate">Filter and Order</span>
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-caret-bottom">
					<use xlink:href="/vendor/clay/icons.svg#caret-bottom" />
				</svg>
			</a>
			<div class="dropdown-menu" role="menu">
				<a class="dropdown-item" href="#1">Action</a>
				<a class="dropdown-item" href="#1">Another action</a>
				<a class="dropdown-item" href="#1">Something else here</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="#1">Separated link</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="#1">One more separated link</a>
			</div>
		</li>
		<li class="nav-item">
			<a class="nav-link" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-import-export">
					<use xlink:href="/vendor/clay/icons.svg#import-export" />
				</svg>
			</a>
		</li>
	</ul>
	<div class="navbar-form navbar-form-autofit navbar-overlay navbar-overlay-sm-down">
		<form role="search">
			<div class="input-group input-group-inset">
				<div class="input-group-input">
					<input class="form-control" placeholder="Search for..." type="text">
				</div>
				<span class="input-group-inset-item">
					<button class="btn btn-link clay-site-close-overlay-sm-down navbar-d-breakpoint-none" type="button">
						<svg aria-hidden="true" class="lexicon-icon lexicon-icon-times">
							<use xlink:href="/vendor/clay/icons.svg#times" />
						</svg>
					</button>
					<button class="btn btn-link navbar-d-breakpoint-block" type="button">
						<svg aria-hidden="true" class="lexicon-icon lexicon-icon-search">
							<use xlink:href="/vendor/clay/icons.svg#search" />
						</svg>
					</button>
				</span>
			</div>
		</form>
	</div>
	<ul class="navbar-nav">
		<li class="nav-item">
			<a class="clay-site-open-overlay-sm-down nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-search">
					<use xlink:href="/vendor/clay/icons.svg#search" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="nav-link navbar-d-breakpoint-block" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-view">
					<use xlink:href="/vendor/clay/icons.svg#view" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="nav-link navbar-d-breakpoint-block" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-table">
					<use xlink:href="/vendor/clay/icons.svg#table" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="btn btn-secondary nav-btn navbar-d-breakpoint-block" href="#1">
				Create Dynamic List
			</a>
			<a class="nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-list">
					<use xlink:href="/vendor/clay/icons.svg#list" />
				</svg>
			</a>
		</li>
	</ul>
</nav>

```xml
<nav class="navbar navbar-expand">
	<ul class="navbar-nav">
		<li class="nav-item">
			<div class="form-check">
				<label class="form-check-label">
					<input class="form-check-input" type="checkbox" value="">
				</label>
			</div>
		</li>
		<li class="dropdown nav-item">
			<a class="nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-magic">
					<use xlink:href="/vendor/clay/icons.svg#magic" />
				</svg>
			</a>
			<a aria-expanded="false" class="dropdown-toggle nav-link navbar-d-breakpoint-block" data-toggle="dropdown" href="#1" role="button">
				<span class="navbar-text-truncate">Filter and Order</span>
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-caret-bottom">
					<use xlink:href="/vendor/clay/icons.svg#caret-bottom" />
				</svg>
			</a>
			<div class="dropdown-menu" role="menu">
				<a class="dropdown-item" href="#1">Action</a>
				<a class="dropdown-item" href="#1">Another action</a>
				<a class="dropdown-item" href="#1">Something else here</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="#1">Separated link</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="#1">One more separated link</a>
			</div>
		</li>
		<li class="nav-item">
			<a class="nav-link" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-import-export">
					<use xlink:href="/vendor/clay/icons.svg#import-export" />
				</svg>
			</a>
		</li>
	</ul>
	<div class="navbar-form navbar-form-autofit navbar-overlay navbar-overlay-sm-down">
		<form role="search">
			<div class="input-group input-group-inset">
				<div class="input-group-input">
					<input class="form-control" placeholder="Search for..." type="text">
				</div>
				<span class="input-group-inset-item">
					<button class="btn btn-link clay-site-close-overlay-sm-down navbar-d-breakpoint-none" type="button">
						<svg aria-hidden="true" class="lexicon-icon lexicon-icon-times">
							<use xlink:href="/vendor/clay/icons.svg#times" />
						</svg>
					</button>
					<button class="btn btn-link navbar-d-breakpoint-block" type="button">
						<svg aria-hidden="true" class="lexicon-icon lexicon-icon-search">
							<use xlink:href="/vendor/clay/icons.svg#search" />
						</svg>
					</button>
				</span>
			</div>
		</form>
	</div>
	<ul class="navbar-nav">
		<li class="nav-item">
			<a class="clay-site-open-overlay-sm-down nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-search">
					<use xlink:href="/vendor/clay/icons.svg#search" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="nav-link navbar-d-breakpoint-block" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-view">
					<use xlink:href="/vendor/clay/icons.svg#view" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="nav-link navbar-d-breakpoint-block" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-table">
					<use xlink:href="/vendor/clay/icons.svg#table" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="btn btn-secondary nav-btn navbar-d-breakpoint-block" href="#1">Create Dynamic List</a>
			<a class="nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-list">
					<use xlink:href="/vendor/clay/icons.svg#list" />
				</svg>
			</a>
		</li>
	</ul>
</nav>

<nav class="navbar navbar-expand navbar-light navbar-light-bg">
	<ul class="navbar-nav">
		<li class="nav-item">
			<div class="form-check">
				<label class="form-check-label">
					<input class="form-check-input" type="checkbox" value="">
				</label>
			</div>
		</li>
		<li class="dropdown nav-item">
			<a class="nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-magic">
					<use xlink:href="/vendor/clay/icons.svg#magic" />
				</svg>
			</a>
			<a aria-expanded="false" class="dropdown-toggle nav-link navbar-d-breakpoint-block" data-toggle="dropdown" href="#1" role="button">
				<span class="navbar-text-truncate">Filter and Order</span>
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-caret-bottom">
					<use xlink:href="/vendor/clay/icons.svg#caret-bottom" />
				</svg>
			</a>
			<div class="dropdown-menu" role="menu">
				<a class="dropdown-item" href="#1">Action</a>
				<a class="dropdown-item" href="#1">Another action</a>
				<a class="dropdown-item" href="#1">Something else here</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="#1">Separated link</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="#1">One more separated link</a>
			</div>
		</li>
		<li class="nav-item">
			<a class="nav-link" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-import-export">
					<use xlink:href="/vendor/clay/icons.svg#import-export" />
				</svg>
			</a>
		</li>
	</ul>
	<div class="navbar-form navbar-form-autofit navbar-overlay navbar-overlay-sm-down">
		<form role="search">
			<div class="input-group input-group-inset">
				<div class="input-group-input">
					<input class="form-control" placeholder="Search for..." type="text">
				</div>
				<span class="input-group-inset-item">
					<button class="btn btn-link clay-site-close-overlay-sm-down navbar-d-breakpoint-none" type="button">
						<svg aria-hidden="true" class="lexicon-icon lexicon-icon-times">
							<use xlink:href="/vendor/clay/icons.svg#times" />
						</svg>
					</button>
					<button class="btn btn-link navbar-d-breakpoint-block" type="button">
						<svg aria-hidden="true" class="lexicon-icon lexicon-icon-search">
							<use xlink:href="/vendor/clay/icons.svg#search" />
						</svg>
					</button>
				</span>
			</div>
		</form>
	</div>
	<ul class="navbar-nav">
		<li class="nav-item">
			<a class="nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="clay-site-open-overlay-sm-down lexicon-icon lexicon-icon-search">
					<use xlink:href="/vendor/clay/icons.svg#search" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="nav-link navbar-d-breakpoint-block" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-view">
					<use xlink:href="/vendor/clay/icons.svg#view" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="nav-link navbar-d-breakpoint-block" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-table">
					<use xlink:href="/vendor/clay/icons.svg#table" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="btn btn-secondary nav-btn navbar-d-breakpoint-block" href="#1">
				Create Dynamic List
			</a>
			<a class="nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-list">
					<use xlink:href="/vendor/clay/icons.svg#list" />
				</svg>
			</a>
		</li>
	</ul>
</nav>

<nav class="navbar navbar-dark navbar-dark-bg navbar-expand">
	<ul class="navbar-nav">
		<li class="nav-item">
			<div class="form-check">
				<label class="form-check-label">
					<input class="form-check-input" type="checkbox" value="">
				</label>
			</div>
		</li>
		<li class="dropdown nav-item">
			<a class="d-md-none nav-link" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-magic">
					<use xlink:href="/vendor/clay/icons.svg#magic" />
				</svg>
			</a>
			<a aria-expanded="false" class="d-md-inline-block d-none dropdown-toggle nav-link" data-toggle="dropdown" href="#1" role="button">
				<span class="navbar-text-truncate">Filter and Order</span>
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-caret-bottom">
					<use xlink:href="/vendor/clay/icons.svg#caret-bottom" />
				</svg>
			</a>
			<div class="dropdown-menu" role="menu">
				<a class="dropdown-item" href="#1">Action</a>
				<a class="dropdown-item" href="#1">Another action</a>
				<a class="dropdown-item" href="#1">Something else here</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="#1">Separated link</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="#1">One more separated link</a>
			</div>
		</li>
		<li class="nav-item">
			<a class="nav-link" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-import-export">
					<use xlink:href="/vendor/clay/icons.svg#import-export" />
				</svg>
			</a>
		</li>
	</ul>
	<div class="navbar-form navbar-form-autofit navbar-overlay navbar-overlay-sm-down">
		<form role="search">
			<div class="input-group input-group-inset">
				<div class="input-group-input">
					<input class="form-control" placeholder="Search for..." type="text">
				</div>
				<span class="input-group-inset-item">
					<button class="btn btn-link clay-site-close-overlay-sm-down navbar-d-breakpoint-none" type="button">
						<svg aria-hidden="true" class="lexicon-icon lexicon-icon-times">
							<use xlink:href="/vendor/clay/icons.svg#times" />
						</svg>
					</button>
					<button class="btn btn-link navbar-d-breakpoint-block" type="button">
						<svg aria-hidden="true" class="lexicon-icon lexicon-icon-search">
							<use xlink:href="/vendor/clay/icons.svg#search" />
						</svg>
					</button>
				</span>
			</div>
		</form>
	</div>
	<ul class="navbar-nav">
		<li class="nav-item">
			<a class="clay-site-open-overlay-sm-down nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-search">
					<use xlink:href="/vendor/clay/icons.svg#search" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="nav-link navbar-d-breakpoint-block" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-view">
					<use xlink:href="/vendor/clay/icons.svg#view" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="nav-link navbar-d-breakpoint-block" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-table">
					<use xlink:href="/vendor/clay/icons.svg#table" />
				</svg>
			</a>
		</li>
		<li class="nav-item">
			<a class="btn btn-secondary nav-btn navbar-d-breakpoint-block" href="#1">
				Create Dynamic List
			</a>
			<a class="nav-link navbar-d-breakpoint-none" href="#1">
				<svg aria-hidden="true" class="lexicon-icon lexicon-icon-list">
					<use xlink:href="/vendor/clay/icons.svg#list" />
				</svg>
			</a>
		</li>
	</ul>
</nav>
```

</article>

<article id="2">

### Navbar Management Bar Example 2

> Use `navbar-overlay navbar-overlay-up` on any direct descendant of navbar to create an overlay on top of the navbar with alternate content, useful for expanding search bars or an alternate navbar that depends on some state in your application. Toggle the `navbar-overlay`'s visibility by adding or removing the class `show` to `navbar-overlay`.

`navbar-overlay-up` overlays the navbar at all screen widths.

`navbar-overlay-lg-down`: 1199px and below

`navbar-overlay-md-down`: 991px and below

`navbar-overlay-sm-down`: 767px and below

`navbar-overlay-xs-down`: 575px and below

<nav class="navbar navbar-expand navbar-light navbar-light-bg">
	<div class="container-fluid container-fluid-max-xxl">
		<ul class="navbar-nav">
			<li class="nav-item">
				<div class="form-check">
					<label class="form-check-label">
						<input class="form-check-input" type="checkbox" value="">
					</label>
				</div>
			</li>
			<li class="dropdown nav-item">
				<a class="nav-link navbar-d-breakpoint-none" href="#1">
					<svg aria-hidden="true" class="lexicon-icon lexicon-icon-magic">
						<use xlink:href="/vendor/clay/icons.svg#magic" />
					</svg>
				</a>
				<a aria-expanded="false" class="dropdown-toggle nav-link navbar-d-breakpoint-block" data-toggle="dropdown" href="#1" role="button">
					<span class="navbar-text-truncate">Filter and Order</span>
					<svg aria-hidden="true" class="lexicon-icon lexicon-icon-caret-bottom">
						<use xlink:href="/vendor/clay/icons.svg#caret-bottom" />
					</svg>
				</a>
				<div class="dropdown-menu" role="menu">
					<a class="dropdown-item" href="#1">Action</a>
					<a class="dropdown-item" href="#1">Another action</a>
					<a class="dropdown-item" href="#1">Something else here</a>
					<div class="dropdown-divider"></div>
					<a class="dropdown-item" href="#1">Separated link</a>
					<div class="dropdown-divider"></div>
					<a class="dropdown-item" href="#1">One more separated link</a>
				</div>
			</li>
			<li class="nav-item">
				<a class="nav-link" href="#1">
					<svg aria-hidden="true" class="lexicon-icon lexicon-icon-import-export">
						<use xlink:href="/vendor/clay/icons.svg#import-export" />
					</svg>
				</a>
			</li>
		</ul>
		<div class="navbar-form navbar-form-autofit navbar-overlay navbar-overlay-sm-down">
			<form role="search">
				<div class="input-group input-group-inset">
					<div class="input-group-input">
						<input class="form-control" placeholder="Search for..." type="text">
					</div>
					<span class="input-group-inset-item">
						<button class="btn btn-link clay-site-close-overlay-sm-down navbar-d-breakpoint-none" type="button">
							<svg aria-hidden="true" class="lexicon-icon lexicon-icon-times">
								<use xlink:href="/vendor/clay/icons.svg#times" />
							</svg>
						</button>
						<button class="btn btn-link navbar-d-breakpoint-block" type="button">
							<svg aria-hidden="true" class="lexicon-icon lexicon-icon-search">
								<use xlink:href="/vendor/clay/icons.svg#search" />
							</svg>
						</button>
					</span>
				</div>
			</form>
		</div>
		<ul class="navbar-nav">
			<li class="nav-item">
				<a class="clay-site-open-overlay-sm-down nav-link navbar-d-breakpoint-none" href="#1">
					<svg aria-hidden="true" class="lexicon-icon lexicon-icon-search">
						<use xlink:href="/vendor/clay/icons.svg#search" />
					</svg>
				</a>
			</li>
			<li class="nav-item">
				<a class="nav-link navbar-d-breakpoint-block" href="#1">
					<svg aria-hidden="true" class="lexicon-icon lexicon-icon-view">
						<use xlink:href="/vendor/clay/icons.svg#view" />
					</svg>
				</a>
			</li>
			<li class="nav-item">
				<a class="nav-link navbar-d-breakpoint-block" href="#1">
					<svg aria-hidden="true" class="lexicon-icon lexicon-icon-table">
						<use xlink:href="/vendor/clay/icons.svg#table" />
					</svg>
				</a>
			</li>
			<li class="nav-item">
				<a class="btn btn-secondary clay-site-open-overlay-up nav-btn" href="#1">
					Open Overlay
				</a>
			</li>
		</ul>
		<div class="navbar-overlay navbar-overlay-up">
			<div class="container-fluid container-fluid-max-xxl">
				<ul class="navbar-nav">
					<li class="nav-item">
						<div class="form-check">
							<label class="form-check-label">
								<input class="form-check-input" type="checkbox" value="">
							</label>
						</div>
					</li>
					<li class="dropdown nav-item">
						<span class="navbar-text">3 of 25</span>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="#1">
							Select All
						</a>
					</li>
				</ul>
				<ul class="navbar-nav">
					<li class="dropdown nav-item">
						<a aria-expanded="false" class="dropdown-toggle nav-link" data-toggle="dropdown" href="#1" role="button">
							<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
								<use xlink:href="/vendor/clay/icons.svg#ellipsis-v" />
							</svg>
						</a>
						<div class="dropdown-menu" role="menu">
							<a class="dropdown-item" href="#1">
								Delete
							</a>
							<a class="dropdown-item" href="#1">
								Copy
							</a>
							<a class="dropdown-item" href="#1">
								Info
							</a>
						</div>
					</li>
					<li class="nav-item">
						<a class="btn btn-secondary clay-site-close-overlay-up nav-btn" href="#1">
							Close Overlay
						</a>
					</li>
				</ul>
			</div>
		</div>
	</div>
</nav>

```xml
<nav class="navbar navbar-expand navbar-light navbar-light-bg">
	<div class="container-fluid container-fluid-max-xxl">
		<ul class="navbar-nav">
			<li class="nav-item">
				<div class="form-check">
					<label class="form-check-label">
						<input class="form-check-input" type="checkbox" value="">
					</label>
				</div>
			</li>
			<li class="dropdown nav-item">
				<a class="nav-link navbar-d-breakpoint-none" href="#1">
					<svg aria-hidden="true" class="lexicon-icon lexicon-icon-magic">
						<use xlink:href="/vendor/clay/icons.svg#magic" />
					</svg>
				</a>
				<a aria-expanded="false" class="dropdown-toggle nav-link navbar-d-breakpoint-block" data-toggle="dropdown" href="#1" role="button">
					<span class="navbar-text-truncate">Filter and Order</span>
					<svg aria-hidden="true" class="lexicon-icon lexicon-icon-caret-bottom">
						<use xlink:href="/vendor/clay/icons.svg#caret-bottom" />
					</svg>
				</a>
				<div class="dropdown-menu" role="menu">
					<a class="dropdown-item" href="#1">Action</a>
					<a class="dropdown-item" href="#1">Another action</a>
					<a class="dropdown-item" href="#1">Something else here</a>
					<div class="dropdown-divider"></div>
					<a class="dropdown-item" href="#1">Separated link</a>
					<div class="dropdown-divider"></div>
					<a class="dropdown-item" href="#1">One more separated link</a>
				</div>
			</li>
			<li class="nav-item">
				<a class="nav-link" href="#1">
					<svg aria-hidden="true" class="lexicon-icon lexicon-icon-import-export">
						<use xlink:href="/vendor/clay/icons.svg#import-export" />
					</svg>
				</a>
			</li>
		</ul>
		<div class="navbar-form navbar-form-autofit navbar-overlay navbar-overlay-sm-down">
			<form role="search">
				<div class="input-group input-group-inset">
					<div class="input-group-input">
						<input class="form-control" placeholder="Search for..." type="text">
					</div>
					<span class="input-group-inset-item">
						<button class="btn btn-link clay-site-close-overlay-sm-down navbar-d-breakpoint-none" type="button">
							<svg aria-hidden="true" class="lexicon-icon lexicon-icon-times">
								<use xlink:href="/vendor/clay/icons.svg#times" />
							</svg>
						</button>
						<button class="btn btn-link navbar-d-breakpoint-block" type="button">
							<svg aria-hidden="true" class="lexicon-icon lexicon-icon-search">
								<use xlink:href="/vendor/clay/icons.svg#search" />
							</svg>
						</button>
					</span>
				</div>
			</form>
		</div>
		<ul class="navbar-nav">
			<li class="nav-item">
				<a class="clay-site-open-overlay-sm-down nav-link navbar-d-breakpoint-none" href="#1">
					<svg aria-hidden="true" class="lexicon-icon lexicon-icon-search">
						<use xlink:href="/vendor/clay/icons.svg#search" />
					</svg>
				</a>
			</li>
			<li class="nav-item">
				<a class="nav-link navbar-d-breakpoint-block" href="#1">
					<svg aria-hidden="true" class="lexicon-icon lexicon-icon-view">
						<use xlink:href="/vendor/clay/icons.svg#view" />
					</svg>
				</a>
			</li>
			<li class="nav-item">
				<a class="nav-link navbar-d-breakpoint-block" href="#1">
					<svg aria-hidden="true" class="lexicon-icon lexicon-icon-table">
						<use xlink:href="/vendor/clay/icons.svg#table" />
					</svg>
				</a>
			</li>
			<li class="nav-item">
				<a class="btn btn-secondary clay-site-open-overlay-up nav-btn" href="#1">
					Open Overlay
				</a>
			</li>
		</ul>
		<div class="navbar-overlay navbar-overlay-up">
			<div class="container-fluid container-fluid-max-xxl">
				<ul class="navbar-nav">
					<li class="nav-item">
						<div class="form-check">
							<label class="form-check-label">
								<input class="form-check-input" type="checkbox" value="">
							</label>
						</div>
					</li>
					<li class="dropdown nav-item">
						<span class="navbar-text">3 of 25</span>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="#1">
							Select All
						</a>
					</li>
				</ul>
				<ul class="navbar-nav">
					<li class="dropdown nav-item">
						<a aria-expanded="false" class="dropdown-toggle nav-link" data-toggle="dropdown" href="#1" role="button">
							<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
								<use xlink:href="/vendor/clay/icons.svg#ellipsis-v" />
							</svg>
						</a>
						<div class="dropdown-menu" role="menu">
							<a class="dropdown-item" href="#1">
								Delete
							</a>
							<a class="dropdown-item" href="#1">
								Copy
							</a>
							<a class="dropdown-item" href="#1">
								Info
							</a>
						</div>
					</li>
					<li class="nav-item">
						<a class="btn btn-secondary clay-site-close-overlay-up nav-btn" href="#1">
							Close Overlay
						</a>
					</li>
				</ul>
			</div>
		</div>
	</div>
</nav>
```

</article>

<article id="3">

### Management Bar

<nav class="navbar navbar-collapse-absolute navbar-expand-md navbar-light navbar-light-bg">
	<div class="container-fluid container-fluid-max-xxl">
		<ul class="navbar-nav">
			<li class="nav-item">
				<div class="form-check">
					<label class="form-check-label">
						<input class="form-check-input" type="checkbox" value="">
					</label>
				</div>
			</li>
			<li class="dropdown nav-item">
				<button class="collapsed navbar-toggler navbar-toggler-link" data-toggle="collapse" href="#mgmtBarCollapse00">
					<span class="navbar-toggler-text">Label</span>
					<svg class="lexicon-icon">
						<use xlink:href="/vendor/clay/icons.svg#caret-double-l" />
					</svg>
				</button>
			</li>
		</ul>
		<div class="collapse navbar-collapse" id="mgmtBarCollapse00">
			<ul class="navbar-nav">
				<li class="dropdown nav-item">
					<a class="dropdown-toggle nav-link" data-toggle="dropdown" href="#1">
						<span class="navbar-text-truncate">Status: Approved, Draft, Pending, Expired</span>
						<svg class="lexicon-icon">
							<use xlink:href="/vendor/clay/icons.svg#caret-double-l" />
						</svg>
					</a>
					<div class="dropdown-menu">
						<form>
							<div class="dropdown-item">
								<select class="form-control">
									<option>1</option>
									<option>2</option>
									<option>3</option>
									<option>4</option>
									<option>5</option>
								</select>
							</div>
							<div class="dropdown-item">
								<label for="exampleInputEmail3">Email address</label>
								<input class="form-control" id="exampleInputEmail3" placeholder="Email" type="email">
							</div>
							<div class="active dropdown-item form-check">
								<label class="form-check-label">
									<input checked class="form-check-input" type="checkbox" value=""> Approved
								</label>
							</div>
							<div class="active dropdown-item form-check">
								<label class="form-check-label">
									<input checked class="form-check-input" type="checkbox" value=""> Draft
								</label>
							</div>
							<div class="active dropdown-item form-check">
								<label class="form-check-label">
									<input checked class="form-check-input" type="checkbox" value=""> Pending
								</label>
							</div>
							<div class="active dropdown-item form-check">
								<label class="form-check-label">
									<input checked class="form-check-input" type="checkbox" value=""> Expired
								</label>
							</div>
							<div class="dropdown-item form-check">
								<label class="form-check-label">
									<input class="form-check-input" type="checkbox" value=""> Scheduled
								</label>
							</div>
							<div class="dropdown-item form-check">
								<label class="form-check-label">
									<input class="form-check-input" type="checkbox" value=""> Rejected
								</label>
							</div>
						</form>
						<a class="dropdown-item" href="#1">Something Outside</a>
					</div>
				</li>
				<li class="dropdown nav-item">
					<a class="dropdown-toggle nav-link" data-toggle="dropdown" href="#1">
						<span class="navbar-text-truncate">Recent</span>
						<svg class="lexicon-icon">
							<use xlink:href="/vendor/clay/icons.svg#caret-double-l" />
						</svg>
					</a>
					<div class="dropdown-menu">
						<a class="dropdown-item" href="#1">All</a>
						<a class="active dropdown-item" href="#1">Recent</a>
						<a class="dropdown-item" href="#1">Mine</a>
					</div>
				</li>
				<li class="dropdown nav-item">
					<a class="dropdown-toggle nav-link" data-toggle="dropdown" href="#1">
						<span class="navbar-text-truncate">Order By: Modified Date</span>
						<svg class="lexicon-icon">
							<use xlink:href="/vendor/clay/icons.svg#caret-double-l" />
						</svg>
					</a>
					<div class="dropdown-menu">
						<a class="dropdown-item" href="#1">Name</a>
						<a class="dropdown-item" href="#1">Create Date</a>
						<a class="active dropdown-item" href="#1">Modified Date</a>
						<a class="dropdown-item" href="#1">Downloads</a>
						<a class="dropdown-item" href="#1">Size</a>
					</div>
				</li>
				<li class="disabled nav-item">
					<a class="nav-link" href="#">
						<span class="navbar-text-truncate">Link</span>
						<span class="sr-only">(current)</span>
					</a>
				</li>
			</ul>
		</div>
		<ul class="navbar-nav">
			<li class="nav-item">
				<a class="nav-link" href="#1">
					<svg class="lexicon-icon lexicon-icon-cards2">
						<use xlink:href="/vendor/clay/icons.svg#cards2" />
					</svg>
				</a>
			</li>
			<li class="nav-item">
				<a class="nav-link" href="#1">
					<svg class="lexicon-icon lexicon-icon-list">
						<use xlink:href="/vendor/clay/icons.svg#list" />
					</svg>
				</a>
			</li>
			<li class="nav-item">
				<a class="nav-link navbar-d-breakpoint-block" href="#1">
					<svg class="lexicon-icon lexicon-icon-table2">
						<use xlink:href="/vendor/clay/icons.svg#table2" />
					</svg>
				</a>
			</li>
		</ul>
	</div>
</nav>

```xml
<nav class="navbar navbar-collapse-absolute navbar-expand-md navbar-light navbar-light-bg">
	<div class="container-fluid container-fluid-max-xxl">
		<ul class="navbar-nav">
			<li class="nav-item">
				<div class="form-check">
					<label class="form-check-label">
						<input class="form-check-input" type="checkbox" value="">
					</label>
				</div>
			</li>
			<li class="dropdown nav-item">
				<button class="collapsed navbar-toggler navbar-toggler-link" data-toggle="collapse" href="#mgmtBarCollapse00">
					<span class="navbar-toggler-text">Label</span>
					<svg class="lexicon-icon">
						<use xlink:href="/vendor/clay/icons.svg#caret-double-l" />
					</svg>
				</button>
			</li>
		</ul>
		<div class="collapse navbar-collapse" id="mgmtBarCollapse00">
			<ul class="navbar-nav">
				<li class="dropdown nav-item">
					<a class="dropdown-toggle nav-link" data-toggle="dropdown" href="#1">
						<span class="navbar-text-truncate">Status: Approved, Draft, Pending, Expired</span>
						<svg class="lexicon-icon">
							<use xlink:href="/vendor/clay/icons.svg#caret-double-l" />
						</svg>
					</a>
					<div class="dropdown-menu">
						<form>
							<div class="dropdown-item">
								<select class="form-control">
									<option>1</option>
									<option>2</option>
									<option>3</option>
									<option>4</option>
									<option>5</option>
								</select>
							</div>
							<div class="dropdown-item">
								<label for="exampleInputEmail3">Email address</label>
								<input class="form-control" id="exampleInputEmail3" placeholder="Email" type="email">
							</div>
							<div class="active dropdown-item form-check">
								<label class="form-check-label">
									<input checked class="form-check-input" type="checkbox" value=""> Approved
								</label>
							</div>
							<div class="active dropdown-item form-check">
								<label class="form-check-label">
									<input checked class="form-check-input" type="checkbox" value=""> Draft
								</label>
							</div>
							<div class="active dropdown-item form-check">
								<label class="form-check-label">
									<input checked class="form-check-input" type="checkbox" value=""> Pending
								</label>
							</div>
							<div class="active dropdown-item form-check">
								<label class="form-check-label">
									<input checked class="form-check-input" type="checkbox" value=""> Expired
								</label>
							</div>
							<div class="dropdown-item form-check">
								<label class="form-check-label">
									<input class="form-check-input" type="checkbox" value=""> Scheduled
								</label>
							</div>
							<div class="dropdown-item form-check">
								<label class="form-check-label">
									<input class="form-check-input" type="checkbox" value=""> Rejected
								</label>
							</div>
						</form>
						<a class="dropdown-item" href="#1">Something Outside</a>
					</div>
				</li>
				<li class="dropdown nav-item">
					<a class="dropdown-toggle nav-link" data-toggle="dropdown" href="#1">
						<span class="navbar-text-truncate">Recent</span>
						<svg class="lexicon-icon">
							<use xlink:href="/vendor/clay/icons.svg#caret-double-l" />
						</svg>
					</a>
					<div class="dropdown-menu">
						<a class="dropdown-item" href="#1">All</a>
						<a class="active dropdown-item" href="#1">Recent</a>
						<a class="dropdown-item" href="#1">Mine</a>
					</div>
				</li>
				<li class="dropdown nav-item">
					<a class="dropdown-toggle nav-link" data-toggle="dropdown" href="#1">
						<span class="navbar-text-truncate">Order By: Modified Date</span>
						<svg class="lexicon-icon">
							<use xlink:href="/vendor/clay/icons.svg#caret-double-l" />
						</svg>
					</a>
					<div class="dropdown-menu">
						<a class="dropdown-item" href="#1">Name</a>
						<a class="dropdown-item" href="#1">Create Date</a>
						<a class="active dropdown-item" href="#1">Modified Date</a>
						<a class="dropdown-item" href="#1">Downloads</a>
						<a class="dropdown-item" href="#1">Size</a>
					</div>
				</li>
				<li class="disabled nav-item">
					<a class="nav-link" href="#">
						<span class="navbar-text-truncate">Link</span>
						<span class="sr-only">(current)</span>
					</a>
				</li>
			</ul>
		</div>
		<ul class="navbar-nav">
			<li class="nav-item">
				<a class="nav-link" href="#1">
					<svg class="lexicon-icon lexicon-icon-cards2">
						<use xlink:href="/vendor/clay/icons.svg#cards2" />
					</svg>
				</a>
			</li>
			<li class="nav-item">
				<a class="nav-link" href="#1">
					<svg class="lexicon-icon lexicon-icon-list">
						<use xlink:href="/vendor/clay/icons.svg#list" />
					</svg>
				</a>
			</li>
			<li class="nav-item">
				<a class="nav-link navbar-d-breakpoint-block" href="#1">
					<svg class="lexicon-icon lexicon-icon-table2">
						<use xlink:href="/vendor/clay/icons.svg#table2" />
					</svg>
				</a>
			</li>
		</ul>
	</div>
</nav>
```

</article>

{literal}
	<script>
		$('select').on('focus', function(event) {
			console.log('hello');
			$(this).closest('.form-group').addClass('focus');
		});
		$('#exampleInputEmail3').on('focus', function(event) {
			console.log('hello');
			$(this).closest('.form-group').addClass('focus');
		});
		$('.form-check-input').on('focus', function(event) {
			console.log('hello');
			$(this).closest('.checkbox').addClass('focus');
		});
		$('.form-check-input').change(function(event) {
			console.log('hello');
			var $this = $(this);
			if ($this.prop('checked')) {
				$this.closest('.checkbox').addClass('active');
			}
			else {
				$this.closest('.checkbox').removeClass('active');
			}
		});
		$('select').on('blur', function(event) {
			console.log('hello');
			$(this).closest('.form-group').removeClass('focus');
		});
		$('#exampleInputEmail3').on('blur', function(event) {
			console.log('hello');
			$(this).closest('.form-group').removeClass('focus');
		});
		$('.form-check-input').on('blur', function(event) {
			console.log('hello');
			$(this).closest('.checkbox').removeClass('focus');
		});
		$('.clay-site-open-overlay-sm-down').on('click', function(event) {
			console.log('hello');
			$(this).closest('.navbar').find('.navbar-overlay-sm-down').addClass('show');
		});
		$('.clay-site-close-overlay-sm-down').on('click', function(event) {
			console.log('hello');
			$(this).closest('.navbar-overlay-sm-down').removeClass('show');
		});
		$('.clay-site-open-overlay-up').on('click', function(event) {
			console.log('hello');
			$(this).closest('.navbar').find('.navbar-overlay-up').addClass('show');
		});
		$('.clay-site-close-overlay-up').on('click', function(event) {
			console.log('hello');
			$(this).closest('.navbar-overlay-up').removeClass('show');
		});
	</script>
{/literal}