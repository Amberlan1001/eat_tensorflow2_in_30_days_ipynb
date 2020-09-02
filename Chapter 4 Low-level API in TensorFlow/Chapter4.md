

<!--
 * @Author       : zch
 * @CreateTime   : 2020-09-02 18:07:08
 * @LastEditTime : 2020-09-02 18:07:54
 * @FilePath     : /eat_tensorflow2_in_30_days_ipynb/Chapter 4 Low-level API in TensorFlow/Chapter4.md
 * @Description  : 
-->
# Chapter 4: Low-level API in TensorFlow

Low-level API of TensorFlow includes tensor operation, graph, automatic differentiate, etc.

If we compare a model to a house, then these low-level APIs are the bricks.

We may use TensorFlow as the enhanced numpy through these low-level APIs.

TensorFlow provides a more complete set of methods comparing to numpy. These methods have higher executiing efficiency and could be further accelerated by GPU if necessary.

We gave an intuitive introduction to the low-level API in the previous sections, and we will emphasize the introduction on the tensor operation and Autograph.

Tensor operation can be devided into two sub-categories: the structural operation and the mathematical operation.

The structural operation includes tensor creation, indexing and slicing, dimension transformation, combining & splitting, etc.

The mathematical operation includes scalar operation, vector operation, and matrix operation. We will also introduce the broadcasting mechanism of tensor operation.

For the part of Autograph, we will cover its suggested rules, its mechanisms `Autograph` and `tf.Module`.


