---
title: "Bayes theorem"
description: "hay!"
date: 2021-08-21T20:55:17+09:00
draft: false
tags: ["Tag 1", "Tag 2"]
categories: ["Category 1", "Category 2"]
---


Let$x$and$y$be random variebles, then they satisfy

$$
p(x|y) = \frac{p(y|x)p(x)}{p(y)}.
$$

This theorem can be easily obtained by a	transformation of joint probability equation as the following.

$$
\begin{split} \\
p(x, y) &= p(y, x) \\
\iff p(x|y)p(y) &= p(y|x)p(x)  \\
\iff p(x|y) &= \frac{p(y|x)p(x)}{p(y)}.
\end{split}
$$
