---
title: Git & Github & Gitlab Flow
author: David
date: 2021-05-27 23:10:29 +0900
categories: [Programming, GitHub]
math: true
viewer: true
tags: [GitHub]
image:
  src: /blog-assets/article-1/title.png?raw=true
  alt: GitHub Pages
---

# Git & Github & Gitlab
> 참고 사이트 : https://ujuc.github.io/2015/12/16/git-flow-github-flow-gitlab-flow/  

> 형상관리를 하는 차원에서는 비슷하지만, Flow의 방식에는 차이가 있다.  

<br>

- ## Git Flow
> feature > develop > release > hotfix > master 브런치가 존재  
 release 브런치와 hotfix 브런치의 경우, develop 브런치의 오른쪽에 존재하기에  
 모두 develop 브런치도 머지를 하도록 구성이 되어있다.

![image](https://user-images.githubusercontent.com/66704969/119842613-c8f1c780-bf41-11eb-9ecf-41df1cd2f3f5.png) 


<br><br>

- ## Github Flow
> Scott chacon은 GitHub Flow에서 GitHub에서 사용하기에는 복잡하다.  
master 브런치에 대한 role만 정확하다면 나머지 브런치들에는 관여를 하지 않는다.  
그리고 pull request 기능을 사용하도록 권장을 한다.

![image](https://cdn-ak.f.st-hatena.com/images/fotolife/s/shoma2da/20151104/20151104223339.png)

#### 특징
- release 브런치가 명확하지 않은 시스템에서 사용에 맞게 되어있다.
- 여기에는 GitHub의 서비스 특성상. 릴리즈라는 개념이 없는 서비스를 진행하고 있어서 그런 것으로 보이며, 웹 서비스들이 릴리즈라는 개념이 없이지고 있으니 사용하기 편할 것으로 보인다.
- hotfix와 가장 작은 기능을 구분하지 않는다. 어차피 둘 다 개발자가 수정해야 되는 일중에 하나이다. 단지 우선순위가 어디가 높냐라는 단계이다.

- ## Gitlab Flow
> Github의 Flow가 단조로워 Staging의 개념이 도입됨

![image](https://about.gitlab.com/images/git_flow/environment_branches.png)
![image](https://about.gitlab.com/images/git_flow/release_branches.png)