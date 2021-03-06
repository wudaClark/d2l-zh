# 优化算法
:label:`chap_optimization`

到目前为止，如果你按顺序阅读本书，你已经学会使用许多优化算法来训练深度学习模型。
它们是允许我们继续更新模型参数和最小化损失函数值的工具。
的确，很多人都愿意将优化视为“黑盒设备”，以最大程度地减少目标函数。
对于他们来说，使用一些深度学习优化“魔法”（如“SGD”和“Adam”之类）就足够了。

然而，想要有效使用优化算法，还需要一些更深层次的知识。
一方面，训练一个复杂的深度学习模型可能需要数小时、数天甚至数周的时间。优化算法的性能直接影响模型的训练效率。
另一方面，了解不同优化算法的原理及其超参数的作用，可以有针对性地调整超参数，提高深度学习模型的性能。

在本章中，我们将深入探讨常见的深度学习优化算法。
在深度学习中，几乎所有的优化问题都是非凸的。
尽管如此，在*凸*问题的背景下设计和分析算法已经被证明是非常有益的。
正是由于这个原因，本章包括了关于凸优化的入门，已经非常简单的随机梯度下降算法在凸目标函数上的证明。

```toc
:maxdepth: 2

optimization-intro
convexity
gd
sgd
minibatch-sgd
momentum
adagrad
rmsprop
adadelta
adam
lr-scheduler
```
