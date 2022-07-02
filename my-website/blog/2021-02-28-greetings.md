---
slug: greetings
title: Greetings!
authors:
  - name: Neel Narayan Shetty
    title: noob c++ kid
    url: https://github.com/Neel-shetty
    image_url: https://avatars.githubusercontent.com/u/71568285?s=96&v=4
  - name: Sébastien Lorber
    title: Docusaurus maintainer
    url: https://sebastienlorber.com
    image_url: https://github.com/slorber.png
tags: [greetings]
---
![Docusaurus logo](/img/docusaurus.png)



Congratulations, you have made your first post!

Do boobs burst or deflate when popped?

Feel free to play around and edit this post as much you like.

```
#include<iostream>
using namespace std;

int main()
{
    cout<<"pog";
}

```
:::tip My tip

Use this awesome feature option

:::

:::danger Take care

This action is dangerous

:::

export const Highlight = ({children, color}) => (
  <span
    style={{
      backgroundColor: color,
      borderRadius: '20px',
      color: '#fff',
      padding: '10px',
      cursor: 'pointer',
    }}
    onClick={() => {
      alert(`You clicked the color ${color} with label ${children}`)
    }}>
    {children}
  </span>
);

This is <Highlight color="#25c2a0">Docusaurus green</Highlight> !

This is <Highlight color="#1877F2">Facebook blue</Highlight> !