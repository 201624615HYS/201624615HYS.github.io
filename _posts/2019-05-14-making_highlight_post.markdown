---
layout: post
title:  "New post with permalink, highlighting"
date:   2019-05-14 13:31:50 +0900
categories: my_own
permalink : dsds
published : true
---
using " { %highlight langagename linenos % } "
{% highlight c linenos %}
#include <stdio.h>

int main() {
  printf("Hello Jekyll!\n");
  return 0;
}
{% endhighlight %}
{% highlight cpp linenos %}
#include <iostream>
using namespace std;

int main() {
  cout<<"Hello Jekyll!"<<endl;

  system("pause");
  return 0;
}
{% endhighlight %}
using " ```langagename "
```cpp
#include <iostream>
using namespace std;

int main() {
  cout<<"Hello Jekyll!"<<endl;

  system("pause");
  return 0;
}
```