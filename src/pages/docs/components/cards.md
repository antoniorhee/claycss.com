---
title: Cards
description: Components
layout: "guide"
weight: 100
---

<article id="1">

### Card

> A container styled like a card for your stuff. Combine different Lexicon components inside a card to create a variety of cards.

<div class="card" style="max-width: 300px;">
    <div class="crop-img crop-img-bottom crop-img-center" style="height: 150px;">
        <img alt="thumbnail" src="../../images/thumbnail_hot_air_ballon.jpg">
    </div>
    <div class="user-icon user-icon-danger user-icon-xxl" style="border: 4px solid #FFF; line-height:120px; margin: -64px auto 0; position: relative;"><span>JB</span></div>
    <div class="card-block" style="text-align: center;">
        <h3 style="margin:0;">Joe Bloggs</h3>
        <h5 class="text-default" style="margin-top:0;">Administrator</h5>
        <p>ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</p>
    </div>
</div>

```xml
<div class="card" style="max-width: 300px;">
    <div class="crop-img crop-img-bottom crop-img-center" style="height: 150px;">
        <img alt="thumbnail" src="../../images/thumbnail_hot_air_ballon.jpg">
    </div>
    <div class="user-icon user-icon-danger user-icon-xxl" style="border: 4px solid #FFF; line-height:120px; margin: -64px auto 0; position: relative;"><span>JB</span></div>
    <div class="card-block" style="text-align: center;">
        <h3 style="margin:0;">Joe Bloggs</h3>
        <h5 class="text-default" style="margin-top:0;">Administrator</h5>
        <p>ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</p>
    </div>
</div>
```

</article>

<article id="2">

### Horizontal Card with Simple Grid

> Use `card-row` with `card-col-content` and `card-col-field` to create a number of custom horizontal cards. `card-col-content` fills the remaining space when used in conjunction with `card-col-field`. `card-col-field` will only be as wide as the content inside.

<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row card-row-padded">
            <div class="card-col-field">
                <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
            </div>
            <div class="card-col-content card-col-gutters">
                <span>This text will fill the remaining space.</span>
            </div>
        </div>
    </div>
</div>

```xml
<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row card-row-padded">
            <div class="card-col-field">
                <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
            </div>
            <div class="card-col-content card-col-gutters">
                <span>This text will fill the remaining space.</span>
            </div>
        </div>
    </div>
</div>
```

</article>

<article id="3">

### Horizontal Cards with Fixed Width Content

> Set a fixed width on the content inside `card-col-field`.

<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row">
            <div class="card-col-field">
                <img alt="thumbnail" src="/images/thumbnail_placeholder.gif" style="width: 150px;">
            </div>
            <div class="card-col-content card-col-gutters">
                <h4>So ristretto cappuccino</h4>
                <p>Wings eu, pumpkin spice robusta.</p>
            </div>
        </div>
    </div>
</div>

<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row card-row-padded">
            <div class="card-col-field">
                <img alt="thumbnail" src="/images/thumbnail_placeholder.gif" style="width: 121px;">
            </div>
            <div class="card-col-content card-col-gutters">
                <h4>So ristretto cappuccino</h4>
                <p>Wings eu, pumpkin spice robusta.</p>
            </div>
        </div>
    </div>
</div>

<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row">
            <div class="card-col-content card-col-gutters">
                <h4>So ristretto cappuccino</h4>
                <p>Wings eu, pumpkin spice robusta.</p>
            </div>
            <div class="card-col-field">
                <img alt="thumbnail" src="/images/thumbnail_placeholder.gif" style="width: 150px;">
            </div>
        </div>
    </div>
</div>

<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row card-row-padded">
            <div class="card-col-content card-col-gutters">
                <h4>So ristretto cappuccino</h4>
                <p>Wings eu, pumpkin spice robusta.</p>
            </div>
            <div class="card-col-field">
                <img alt="thumbnail" src="/images/thumbnail_placeholder.gif" style="width: 121px;">
            </div>
        </div>
    </div>
</div>

<div class="col-md-8">
    <div class="card card-horizontal">
        <div class="card-row card-row-padded">
            <div class="card-col-field">
                <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
            </div>
            <div class="card-col-content card-col-gutters">
                <span>Really super insanely just incredibly long and totally not possible word. ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
            </div>
            <div class="card-col-field">
                <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
            </div>
        </div>
    </div>
</div>

```xml
<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row">
            <div class="card-col-field">
                <img alt="thumbnail" src="/images/thumbnail_placeholder.gif" style="width: 150px;">
            </div>

            <div class="card-col-content card-col-gutters">
                <h4>So ristretto cappuccino</h4>

                <p>Wings eu, pumpkin spice robusta.</p>
            </div>
        </div>
    </div>
</div>

<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row card-row-padded">
            <div class="card-col-field">
                <img alt="thumbnail" src="/images/thumbnail_placeholder.gif" style="width: 121px;">
            </div>

            <div class="card-col-content card-col-gutters">
                <h4>So ristretto cappuccino</h4>

                <p>Wings eu, pumpkin spice robusta.</p>
            </div>
        </div>
    </div>
</div>

<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row">
            <div class="card-col-content card-col-gutters">
                <h4>So ristretto cappuccino</h4>

                <p>Wings eu, pumpkin spice robusta.</p>
            </div>
            <div class="card-col-field">
                <img alt="thumbnail" src="/images/thumbnail_placeholder.gif" style="width: 150px;">
            </div>
        </div>
    </div>
</div>

<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row card-row-padded">
            <div class="card-col-content card-col-gutters">
                <h4>So ristretto cappuccino</h4>

                <p>Wings eu, pumpkin spice robusta.</p>
            </div>
            <div class="card-col-field">
                <img alt="thumbnail" src="/images/thumbnail_placeholder.gif" style="width: 121px;">
            </div>
        </div>
    </div>
</div>

<div class="col-md-8">
    <div class="card card-horizontal">
        <div class="card-row card-row-padded">
            <div class="card-col-field">
                <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
            </div>
            <div class="card-col-content card-col-gutters">
                <span>Really super insanely just incredibly long and totally not possible word. ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
            </div>
            <div class="card-col-field">
                <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
            </div>
        </div>
    </div>
</div>

```

</article>

<article id="4">

### Truncating Text Inside Card

> Add class `truncate-text` on whatever text you want to be truncated.

<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row card-row-padded">
            <div class="card-col-field">
                <img alt="thumbnail" src="../../images/thumbnail_placeholder.gif" style="width: 150px;">
            </div>
            <div class="card-col-content card-col-gutters">
                <h4>So ristretto cappuccino</h4>
                <p class="truncate-text">Wings eu, pumpkin spice robusta, kopi-luwak mocha caffeine froth grounds.</p>
            </div>
        </div>
    </div>
</div>

<ul class="list-unstyled" style="clear:both;">
    <li class="col-md-6">
        <div class="card card-horizontal">
            <div class="card-row card-row-padded">
                <div class="card-col-field">
                    <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                </div>
                <div class="card-col-content card-col-gutters">
                    <h4 class="truncate-text" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</h4>
                </div>
                <div class="card-col-field">
                    <div class="dropdown">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </li>
    <li class="col-md-6">
        <div class="card card-horizontal">
            <div class="card-row card-row-padded">
                <div class="card-col-field">
                    <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                </div>
                <div class="card-col-content card-col-gutters">
                    <h4 title="Folder 01">Folder 01</h4>
                </div>
                <div class="card-col-field">
                    <div class="dropdown">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </li>
    <li class="col-md-6">
        <div class="card card-horizontal">
            <div class="card-row card-row-padded">
                <div class="card-col-field">
                    <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                </div>
                <div class="card-col-content card-col-gutters">
                    <h4 title="Folder 02">Folder 02</h4>
                </div>
                <div class="card-col-field">
                    <div class="dropdown">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </li>
    <li class="col-md-6">
        <div class="card card-horizontal">
            <div class="card-row card-row-padded">
                <div class="card-col-field">
                    <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                </div>
                <div class="card-col-content card-col-gutters">
                    <h4 title="Folder 03">Folder 03</h4>
                </div>
                <div class="card-col-field">
                    <div class="dropdown">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </li>
</ul>

```xml
<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row card-row-padded">
            <div class="card-col-field">
                <img alt="thumbnail" src="../../images/thumbnail_placeholder.gif" style="width: 150px;">
            </div>

            <div class="card-col-content card-col-gutters">
                <h4>So ristretto cappuccino</h4>
                <p class="truncate-text">Wings eu, pumpkin spice robusta, kopi-luwak mocha caffeine froth grounds.</p>
            </div>
        </div>
    </div>
</div>

<ul class="list-unstyled" style="clear:both;">
    <li class="col-md-6">
        <div class="card card-horizontal">
            <div class="card-row card-row-padded">
                <div class="card-col-field">
                    <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                </div>
                <div class="card-col-content card-col-gutters">
                    <h4 class="truncate-text" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</h4>
                </div>
                <div class="card-col-field">
                    <div class="dropdown">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </li>

    <li class="col-md-6">
        <div class="card card-horizontal">
            <div class="card-row card-row-padded">
                <div class="card-col-field">
                    <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                </div>
                <div class="card-col-content card-col-gutters">
                    <h4 title="Folder 01">Folder 01</h4>
                </div>
                <div class="card-col-field">
                    <div class="dropdown">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </li>

    <li class="col-md-6">
        <div class="card card-horizontal">
            <div class="card-row card-row-padded">
                <div class="card-col-field">
                    <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                </div>
                <div class="card-col-content card-col-gutters">
                    <h4 title="Folder 02">Folder 02</h4>
                </div>
                <div class="card-col-field">
                    <div class="dropdown">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </li>

    <li class="col-md-6">
        <div class="card card-horizontal">
            <div class="card-row card-row-padded">
                <div class="card-col-field">
                    <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                </div>
                <div class="card-col-content card-col-gutters">
                    <h4 title="Folder 03">Folder 03</h4>
                </div>
                <div class="card-col-field">
                    <div class="dropdown">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </li>
</ul>
```

</article>

<article id="5">

### Card Row Vertical Alignment Helpers

> Vertically align content by setting the css property `vertical-align` on the card-col and align content horizontally by using `text-align` or use the helper classes `card-row-valign-bottom` and `card-row-valign-top` on the `card-row` to vertically align all columns inside the row.

<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row">
            <div class="card-col-field" style="vertical-align: top;">top</div>
            <div class="card-col-field">middle</div>
            <div class="card-col-field" style="vertical-align: bottom;">bottom</div>
        </div>
    </div>
</div>

<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row">
            <div class="card-col-field" style="text-align:left;">left</div>
            <div class="card-col-field">center</div>
            <div class="card-col-field" style="text-align:right;">right</div>
        </div>
    </div>
</div>

```xml
<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row">
            <div class="card-col-field" style="vertical-align: top;">top</div>
            <div class="card-col-field">middle</div>
            <div class="card-col-field" style="vertical-align: bottom;">bottom</div>
        </div>
    </div>
</div>

<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row">
            <div class="card-col-field" style="text-align:left;">left</div>
            <div class="card-col-field">center</div>
            <div class="card-col-field" style="text-align:right;">right</div>
        </div>
    </div>
</div>
```

> Add gutters to a specific card card column by using the class `card-col-gutters`.

<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row">
            <div class="card-col-field">
                <img alt="thumbnail" src="/images/thumbnail_placeholder.gif" style="width: 150px;">
            </div>
            <div class="card-col-content card-col-gutters">
                <h4>So ristretto cappuccino</h4>
                <p>Wings eu, pumpkin spice robusta.</p>
            </div>
        </div>
    </div>
</div>

```xml
<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row">
            <div class="card-col-field">
                <img alt="thumbnail" src="/images/thumbnail_placeholder.gif" style="width: 150px;">
            </div>

            <div class="card-col-content card-col-gutters">
                <h4>So ristretto cappuccino</h4>

                <p>Wings eu, pumpkin spice robusta.</p>
            </div>
        </div>
    </div>
</div>
```

> Use `card-row-padded` on `card-row` to add some spacing around a horizontal card.

<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row card-row-padded">
            <div class="card-col-field">
                <img alt="thumbnail" src="/images/thumbnail_placeholder.gif" style="width: 121px;">
            </div>
            <div class="card-col-content card-col-gutters">
                <h4>So ristretto cappuccino</h4>
                <p>Wings eu, pumpkin spice robusta.</p>
            </div>
        </div>
    </div>
</div>

```xml
<div class="col-md-6">
    <div class="card card-horizontal">
        <div class="card-row card-row-padded">
            <div class="card-col-field">
                <img alt="thumbnail" src="/images/thumbnail_placeholder.gif" style="width: 121px;">
            </div>

            <div class="card-col-content card-col-gutters">
                <h4>So ristretto cappuccino</h4>
                <p>Wings eu, pumpkin spice robusta.</p>
            </div>
        </div>
    </div>
</div>
```

</article>

<article id="6">

### Card Helper Classes

> Use classes `card-rounded`, `card-circle`, or `card-square` on the card to quickly shape the borders.

<div class="col-md-4 uxgl-horizontal-card">
    <div class="card card-horizontal card-rounded">
        <div class="card-row">
            <div class="card-col-field">card-col-field</div>
            <div class="card-col-field">card-col-field</div>
        </div>
    </div>
</div>

<div class="col-md-4 uxgl-horizontal-card">
    <div class="card card-circle card-horizontal">
        <div class="card-row">
            <div class="card-col-field">card-col-field</div>
            <div class="card-col-field">card-col-field</div>
        </div>
    </div>
</div>

<div class="col-md-4 uxgl-horizontal-card">
    <div class="card card-horizontal card-square">
        <div class="card-row">
            <div class="card-col-field">card-col-field</div>
            <div class="card-col-field">card-col-field</div>
        </div>
    </div>
</div>

```xml
<div class="col-md-4 uxgl-horizontal-card">
    <div class="card card-horizontal card-rounded">
        <div class="card-row">
            <div class="card-col-field">card-col-field</div>
            <div class="card-col-field">card-col-field</div>
        </div>
    </div>
</div>

<div class="col-md-4 uxgl-horizontal-card">
    <div class="card card-circle card-horizontal">
        <div class="card-row">
            <div class="card-col-field">card-col-field</div>
            <div class="card-col-field">card-col-field</div>
        </div>
    </div>
</div>

<div class="col-md-4 uxgl-horizontal-card">
    <div class="card card-horizontal card-square">
        <div class="card-row">
            <div class="card-col-field">card-col-field</div>
            <div class="card-col-field">card-col-field</div>
        </div>
    </div>
</div>
```

> We didn't add `overflow: hidden` to the `card` class because it prevents nested dropdowns, popups, and tooltips from fully displaying. You can work around this by adding `border-radius` to the image or `overflow: hidden` to the card.

<div class="alert alert-warning">
    When using card border helper classes with images as the first or last item, add the css property <span class="text-danger">overflow: hidden</span> to the card or <span class="text-danger">border-radius</span> to the image.
</div>

<div class="col-md-4 col-xs-6">
    <div class="card card-rounded" style="overflow: hidden;">
        <div class="aspect-ratio aspect-ratio-16-to-9">
            <img alt="thumbnail" src="../../images/thumbnail_hot_air_ballon.jpg">
        </div>
        <div class="card-row card-row-padded card-row-valign-top">
            <div class="card-col-content" style="height: 125px; text-align: center;">
                <h3 style="margin:0;">Joe Bloggs</h3>
                <h5 class="text-default" style="margin-top:0;">Administrator</h5>
                <p>Wings eu, pumpkin spice robusta, kopi-luwak mocha caffeine froth grounds.</p>
            </div>
        </div>
    </div>
</div>

<div class="col-md-6 col-sm-12 col-xs-12">
    <div class="card card-horizontal card-rounded">
        <div class="card-row card-row-valign-top">
            <div class="card-col-field">
                <img src="../../images/thumbnail_dock.jpg" style="border-radius: 4px 0 0 4px;width: 150px;" />
            </div>
            <div class="card-col-content card-col-gutters">
                <h4>Space Program</h4>
                <div class="divider"></div>
                <p>Because you live life on the edge of space.</p>
            </div>
        </div>
    </div>
</div>

```xml
<div class="col-md-4 col-xs-6">
    <div class="card card-rounded" style="overflow: hidden;">
        <div class="aspect-ratio aspect-ratio-16-to-9">
            <img alt="thumbnail" src="../../images/thumbnail_hot_air_ballon.jpg">
        </div>

        <div class="card-row card-row-padded card-row-valign-top">
            <div class="card-col-content" style="height: 125px; text-align: center;">
                <h3 style="margin:0;">Joe Bloggs</h3>
                <h5 class="text-default" style="margin-top:0;">Administrator</h5>
                <p>Wings eu, pumpkin spice robusta, kopi-luwak mocha caffeine froth grounds.</p>
            </div>
        </div>
    </div>
</div>

<div class="col-md-6 col-sm-12 col-xs-12">
    <div class="card card-horizontal card-rounded">
        <div class="card-row card-row-valign-top">
            <div class="card-col-field">
                <img src="../../images/thumbnail_dock.jpg" style="border-radius: 4px 0 0 4px;width: 150px;" />
            </div>
            <div class="card-col-content card-col-gutters">
                <h4>Space Program</h4>
                <div class="divider"></div>
                <p>Because you live life on the edge of space.</p>
            </div>
        </div>
    </div>
</div>
```

</article>

<article id="7">

### Card Dividers

> Use `<div class="divider"></div>` to create a horizontal division between content inside a card.

<div class="col-md-6 uxgl-horizontal-card">
    <div class="card card-horizontal">
        <div class="card-row">
            <div class="card-col-field">
                card-col-field
            </div>
            <div class="card-col-field card-col-gutters">
                <h4>Title</h4>
                <div class="divider"></div>
                <p>card-col-field</p>
            </div>
        </div>
    </div>
</div>

```xml
<div class="col-md-6 uxgl-horizontal-card">
    <div class="card card-horizontal">
        <div class="card-row">
            <div class="card-col-field">
                card-col-field
            </div>
            <div class="card-col-field card-col-gutters">
                <h4>Title</h4>
                <div class="divider"></div>
                <p>card-col-field</p>
            </div>
        </div>
    </div>
</div>
```

</article>

<article id="8">

### Checkbox Card

> We have created a pattern to add checkboxes to cards, just wrap the checkbox and card in:

```xml
<div class="checkbox checkbox-card checkbox-top-left">
    <label>
        <input type="checkbox">
    </label>
    <div class="card">...</div>
</div>
```

<div class="col-xs-4 col-md-4">
    <div class="checkbox checkbox-card checkbox-top-left">
        <label>
            <input type="checkbox">
        </label>
        <div class="card">
            <div class="aspect-ratio">
                <img alt="thumbnail" src="../../images/thumbnail_coffee.jpg">
                <span class="sticker sticker-bottom sticker-warning">PNG</span>
            </div>
            <div class="card-row card-row-padded card-row-valign-top">
                <div class="card-col-content">
                    <span class="truncate-text">Aldcott Gage George Polwarth-Kitchener</span>
                    <span class="truncate-text" title="thumbnail_dock.jpg">thumbnail_dock.jpg</span>
                    <span class="truncate-text">Approved</span>
                </div>
                <div class="card-col-field">
                    <div class="dropdown" style="margin-right: -8px;">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="col-xs-8 col-md-8">
    <div class="checkbox checkbox-card checkbox-middle-left">
        <label>
            <input type="checkbox" value="">
        </label>
        <div class="card card-horizontal">
            <div class="card-row card-row-padded">
                <div class="card-col-field">
                    <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                </div>
                <div class="card-col-content card-col-gutters">
                    <span class="truncate-text" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
                </div>
                <div class="card-col-field">
                    <div class="dropdown">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

```xml
<div class="col-xs-4 col-md-4">
    <div class="checkbox checkbox-card checkbox-top-left">
        <label>
            <input type="checkbox">
        </label>
        <div class="card">
            <div class="aspect-ratio">
                <img alt="thumbnail" src="../../images/thumbnail_coffee.jpg">
                <span class="sticker sticker-bottom sticker-warning">PNG</span>
            </div>
            <div class="card-row card-row-padded card-row-valign-top">
                <div class="card-col-content">
                    <span class="truncate-text">Aldcott Gage George Polwarth-Kitchener</span>
                    <span class="truncate-text" title="thumbnail_dock.jpg">thumbnail_dock.jpg</span>
                    <span class="truncate-text">Approved</span>
                </div>

                <div class="card-col-field">
                    <div class="dropdown" style="margin-right: -8px;">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="col-xs-8 col-md-8">
    <div class="checkbox checkbox-card checkbox-middle-left">
        <label>
            <input type="checkbox" value="">
        </label>
        <div class="card card-horizontal">
            <div class="card-row card-row-padded">
                <div class="card-col-field">
                    <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                </div>
                <div class="card-col-content card-col-gutters">
                    <span class="truncate-text" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
                </div>
                <div class="card-col-field">
                    <div class="dropdown">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
```

</article>

<article id="9">

### Clickable Checkbox Card

> To make the whole card clickable just wrap the checkbox and card in:

```xml
<div class="checkbox checkbox-card checkbox-top-left">
    <label>
        <input type="checkbox">
        <div class="card">...</div>
    </label>
</div>
```

<div class="col-xs-4 col-md-4">
    <div class="checkbox checkbox-card checkbox-top-left">
        <label>
            <input type="checkbox">
            <div class="card">
                <div class="aspect-ratio">
                    <img alt="thumbnail" src="../../images/thumbnail_coffee.jpg">
                    <span class="sticker sticker-bottom sticker-warning">PNG</span>
                </div>
                <div class="card-row card-row-padded card-row-valign-top">
                    <div class="card-col-content">
                        <span class="truncate-text">Aldcott Gage George Polwarth-Kitchener</span>
                        <span class="truncate-text" title="thumbnail_dock.jpg">thumbnail_dock.jpg</span>
                        <span class="truncate-text">Approved</span>
                    </div>
                    <div class="card-col-field">
                        <div class="dropdown" style="margin-right: -8px;">
                            <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                                <svg aria-hidden="true" class="lexicon-icon">
                                    <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                                </svg>
                            </a>
                            <ul class="dropdown-menu dropdown-menu-right">
                                <li><a href="#1">Download</a></li>
                                <li><a href="#1">Edit</a></li>
                                <li><a href="#1">Move</a></li>
                                <li><a href="#1">Checkout</a></li>
                                <li><a href="#1">Permissions</a></li>
                                <li><a href="#1">Move to Recycle Bin</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </label>
    </div>
</div>

<div class="col-xs-8 col-md-8">
    <div class="checkbox checkbox-card checkbox-middle-left">
        <label>
            <input type="checkbox" value="">
            <div class="card card-horizontal">
                <div class="card-row card-row-padded">
                    <div class="card-col-field">
                        <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                    </div>
                    <div class="card-col-content card-col-gutters">
                        <span class="truncate-text" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
                    </div>
                    <div class="card-col-field">
                        <div class="dropdown">
                            <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                                <svg aria-hidden="true" class="lexicon-icon">
                                    <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                                </svg>
                            </a>
                            <ul class="dropdown-menu dropdown-menu-right">
                                <li><a href="#1">Download</a></li>
                                <li><a href="#1">Edit</a></li>
                                <li><a href="#1">Move</a></li>
                                <li><a href="#1">Checkout</a></li>
                                <li><a href="#1">Permissions</a></li>
                                <li><a href="#1">Move to Recycle Bin</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </label>
    </div>
</div>

```xml
<div class="col-xs-4 col-md-4">
    <div class="checkbox checkbox-card checkbox-top-left">
        <label>
            <input type="checkbox">
            <div class="card">
                <div class="aspect-ratio">
                    <img alt="thumbnail" src="../../images/thumbnail_coffee.jpg">
                    <span class="sticker sticker-bottom sticker-warning">PNG</span>
                </div>
                <div class="card-row card-row-padded card-row-valign-top">
                    <div class="card-col-content">
                        <span class="truncate-text">Aldcott Gage George Polwarth-Kitchener</span>
                        <span class="truncate-text" title="thumbnail_dock.jpg">thumbnail_dock.jpg</span>
                        <span class="truncate-text">Approved</span>
                    </div>

                    <div class="card-col-field">
                        <div class="dropdown" style="margin-right: -8px;">
                            <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                                <svg aria-hidden="true" class="lexicon-icon">
                                    <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                                </svg>
                            </a>
                            <ul class="dropdown-menu dropdown-menu-right">
                                <li><a href="#1">Download</a></li>
                                <li><a href="#1">Edit</a></li>
                                <li><a href="#1">Move</a></li>
                                <li><a href="#1">Checkout</a></li>
                                <li><a href="#1">Permissions</a></li>
                                <li><a href="#1">Move to Recycle Bin</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </label>
    </div>
</div>

<div class="col-xs-8 col-md-8">
    <div class="checkbox checkbox-card checkbox-middle-left">
        <label>
            <input type="checkbox" value="">
            <div class="card card-horizontal">
                <div class="card-row card-row-padded">
                    <div class="card-col-field">
                        <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                    </div>
                    <div class="card-col-content card-col-gutters">
                        <span class="truncate-text" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
                    </div>
                    <div class="card-col-field">
                        <div class="dropdown">
                            <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                                <svg aria-hidden="true" class="lexicon-icon">
                                    <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                                </svg>
                            </a>
                            <ul class="dropdown-menu dropdown-menu-right">
                                <li><a href="#1">Download</a></li>
                                <li><a href="#1">Edit</a></li>
                                <li><a href="#1">Move</a></li>
                                <li><a href="#1">Checkout</a></li>
                                <li><a href="#1">Permissions</a></li>
                                <li><a href="#1">Move to Recycle Bin</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </label>
    </div>
</div>
```

</article>

<article id="10">

### Radio Card

> We have created a pattern to add radio inputs to cards, just wrap the radio input and card in:

```xml
<div class="radio radio-card radio-top-left">
    <label>
        <input type="radio">
    </label>
    <div class="card">...</div>
</div>
```

<div class="col-xs-4 col-md-4">
    <div class="radio radio-card radio-top-left">
        <label>
            <input name="cardRadios1" type="radio" value="cardOption1">
        </label>
        <div class="card">
            <div class="aspect-ratio">
                <img alt="thumbnail" src="../../images/thumbnail_coffee.jpg">
                <span class="sticker sticker-bottom sticker-warning">PNG</span>
            </div>
            <div class="card-row card-row-padded card-row-valign-top">
                <div class="card-col-content">
                    <span class="truncate-text">Aldcott Gage George Polwarth-Kitchener</span>
                    <span class="truncate-text" title="thumbnail_dock.jpg">thumbnail_dock.jpg</span>
                    <span class="truncate-text">Approved</span>
                </div>
                <div class="card-col-field">
                    <div class="dropdown" style="margin-right: -8px;">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="col-xs-8 col-md-8">
    <div class="radio radio-card radio-middle-left">
        <label>
            <input name="cardRadios1" type="radio" value="cardOption2">
        </label>
        <div class="card card-horizontal">
            <div class="card-row card-row-padded">
                <div class="card-col-field">
                    <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                </div>
                <div class="card-col-content card-col-gutters">
                    <span class="truncate-text" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
                </div>
                <div class="card-col-field">
                    <div class="dropdown">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

```xml
<div class="col-xs-4 col-md-4">
    <div class="radio radio-card radio-top-left">
        <label>
            <input name="cardRadios1" type="radio" value="cardOption1">
        </label>
        <div class="card">
            <div class="aspect-ratio">
                <img alt="thumbnail" src="../../images/thumbnail_coffee.jpg">
                <span class="sticker sticker-bottom sticker-warning">PNG</span>
            </div>
            <div class="card-row card-row-padded card-row-valign-top">
                <div class="card-col-content">
                    <span class="truncate-text">Aldcott Gage George Polwarth-Kitchener</span>
                    <span class="truncate-text" title="thumbnail_dock.jpg">thumbnail_dock.jpg</span>
                    <span class="truncate-text">Approved</span>
                </div>

                <div class="card-col-field">
                    <div class="dropdown" style="margin-right: -8px;">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="col-xs-8 col-md-8">
    <div class="radio radio-card radio-middle-left">
        <label>
            <input name="cardRadios1" type="radio" value="cardOption2">
        </label>
        <div class="card card-horizontal">
            <div class="card-row card-row-padded">
                <div class="card-col-field">
                    <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                </div>
                <div class="card-col-content card-col-gutters">
                    <span class="truncate-text" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
                </div>
                <div class="card-col-field">
                    <div class="dropdown">
                        <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                            <svg aria-hidden="true" class="lexicon-icon">
                                <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                            </svg>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <li><a href="#1">Download</a></li>
                            <li><a href="#1">Edit</a></li>
                            <li><a href="#1">Move</a></li>
                            <li><a href="#1">Checkout</a></li>
                            <li><a href="#1">Permissions</a></li>
                            <li><a href="#1">Move to Recycle Bin</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
```

</article>

<article id="11">

### Clickable Radio Card

> To make the whole card clickable just wrap the radio input and card in:

```xml
<div class="radio radio-card radio-top-left">
    <label>
        <input type="radio">
        <div class="card">...</div>
    </label>
</div>
```

<div class="col-xs-4 col-md-4">
    <div class="radio radio-card radio-top-left">
        <label>
            <input name="cardRadios" type="radio" value="cardOption1">
            <div class="card">
                <div class="aspect-ratio">
                    <img alt="thumbnail" src="../../images/thumbnail_coffee.jpg">
                    <span class="sticker sticker-bottom sticker-warning">PNG</span>
                </div>
                <div class="card-row card-row-padded card-row-valign-top">
                    <div class="card-col-content">
                        <span class="truncate-text">Aldcott Gage George Polwarth-Kitchener</span>
                        <span class="truncate-text" title="thumbnail_dock.jpg">thumbnail_dock.jpg</span>
                        <span class="truncate-text">Approved</span>
                    </div>
                    <div class="card-col-field">
                        <div class="dropdown" style="margin-right: -8px;">
                            <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                                <svg aria-hidden="true" class="lexicon-icon">
                                    <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                                </svg>
                            </a>
                            <ul class="dropdown-menu dropdown-menu-right">
                                <li><a href="#1">Download</a></li>
                                <li><a href="#1">Edit</a></li>
                                <li><a href="#1">Move</a></li>
                                <li><a href="#1">Checkout</a></li>
                                <li><a href="#1">Permissions</a></li>
                                <li><a href="#1">Move to Recycle Bin</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </label>
    </div>
</div>

<div class="col-xs-8 col-md-8">
    <div class="radio radio-card radio-middle-left">
        <label>
            <input name="cardRadios" type="radio" value="cardOption2">
            <div class="card card-horizontal">
                <div class="card-row card-row-padded">
                    <div class="card-col-field">
                        <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                    </div>
                    <div class="card-col-content card-col-gutters">
                        <span class="truncate-text" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
                    </div>
                    <div class="card-col-field">
                        <div class="dropdown">
                            <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                                <svg aria-hidden="true" class="lexicon-icon">
                                    <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                                </svg>
                            </a>
                            <ul class="dropdown-menu dropdown-menu-right">
                                <li><a href="#1">Download</a></li>
                                <li><a href="#1">Edit</a></li>
                                <li><a href="#1">Move</a></li>
                                <li><a href="#1">Checkout</a></li>
                                <li><a href="#1">Permissions</a></li>
                                <li><a href="#1">Move to Recycle Bin</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </label>
    </div>
</div>

```xml
<div class="col-xs-4 col-md-4">
    <div class="radio radio-card radio-top-left">
        <label>
            <input name="cardRadios" type="radio" value="cardOption1">
            <div class="card">
                <div class="aspect-ratio">
                    <img alt="thumbnail" src="../../images/thumbnail_coffee.jpg">
                    <span class="sticker sticker-bottom sticker-warning">PNG</span>
                </div>
                <div class="card-row card-row-padded card-row-valign-top">
                    <div class="card-col-content">
                        <span class="truncate-text">Aldcott Gage George Polwarth-Kitchener</span>
                        <span class="truncate-text" title="thumbnail_dock.jpg">thumbnail_dock.jpg</span>
                        <span class="truncate-text">Approved</span>
                    </div>

                    <div class="card-col-field">
                        <div class="dropdown" style="margin-right: -8px;">
                            <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                                <svg aria-hidden="true" class="lexicon-icon">
                                    <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                                </svg>
                            </a>
                            <ul class="dropdown-menu dropdown-menu-right">
                                <li><a href="#1">Download</a></li>
                                <li><a href="#1">Edit</a></li>
                                <li><a href="#1">Move</a></li>
                                <li><a href="#1">Checkout</a></li>
                                <li><a href="#1">Permissions</a></li>
                                <li><a href="#1">Move to Recycle Bin</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </label>
    </div>
</div>

<div class="col-xs-8 col-md-8">
    <div class="radio radio-card radio-middle-left">
        <label>
            <input name="cardRadios" type="radio" value="cardOption2">
            <div class="card card-horizontal">
                <div class="card-row card-row-padded">
                    <div class="card-col-field">
                        <span class="icon-folder-close-alt sticker sticker-default sticker-static sticker-lg"></span>
                    </div>
                    <div class="card-col-content card-col-gutters">
                        <span class="truncate-text" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
                    </div>
                    <div class="card-col-field">
                        <div class="dropdown">
                            <a class="dropdown-toggle icon-monospaced" data-toggle="dropdown" href="#1">
                                <svg aria-hidden="true" class="lexicon-icon">
                                    <use xlink:href="/vendor/lexicon/icons.svg#ellipsis-v" />
                                </svg>
                            </a>
                            <ul class="dropdown-menu dropdown-menu-right">
                                <li><a href="#1">Download</a></li>
                                <li><a href="#1">Edit</a></li>
                                <li><a href="#1">Move</a></li>
                                <li><a href="#1">Checkout</a></li>
                                <li><a href="#1">Permissions</a></li>
                                <li><a href="#1">Move to Recycle Bin</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </label>
    </div>
</div>
```

</article>
