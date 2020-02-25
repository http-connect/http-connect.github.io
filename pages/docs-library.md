---
layout: default
permalink: /docs/library
title: Library
description: Documentation
---

{% include page_heading.html page=page %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent eu neque eget arcu vestibulum vulputate. Pellentesque vestibulum ullamcorper quam, at tristique risus faucibus in. Phasellus quis nunc nec libero pretium tincidunt. Fusce sit amet interdum velit. Fusce scelerisque mattis ipsum, eget hendrerit augue molestie a. Duis eu fringilla libero. Fusce laoreet purus enim, eu eleifend odio eleifend ut. Quisque rhoncus lorem eget ullamcorper ultricies. Nam auctor lectus odio, ac faucibus mauris dignissim vel.

{% highlight php linenos %}
<?php

declare(strict_types=1);

namespace HttpConnect\Standard;

use HttpConnect\Standard\Validation\ValidatorMetadataInterface;

interface InputInterface extends ValidatorMetadataInterface
{
    /**
     * @return string
     */
    public function __toString(): string;
}
{% endhighlight %}
