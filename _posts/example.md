---
layout: post
title:  "Example Post"
date:   2022-01-28 12:28:52 +0900
categories: Algorithm
---

Follow the flow.

{% highlight C++ %}
#include <iostream>
#include <queue>
using namespace std;

int main() {
    priority_queue<int, vector<int>, greater<int> > Q;
    int a; cin >> a; Q.push(a);
    cout << Q.top(); Q.pop();
    return 0;
}
{% endhighlight %}

