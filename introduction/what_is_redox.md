Redox — что это?
==============

Вероятно Вы все еще задаете себе вопрос: что же все-таки это такое?

Redox это попытка сделать законченную, полнофункциональную операционную систему общего назначения сфокусированную на безопасности, надежности, правильности (correctness) и прагматизме.

Цель Redox
------------------

We want to be able to use it, without obstructions, as a alternative to Linux on our computers. It should be able to run pretty most Linux programs with only minimal modifications.

We're aiming towards a complete, safe Rust ecosystem. This is a design choice, which hopefully improves correctness and security (see `Why Rust?`).

We want to improve the security design when compared to other Unix-like kernels by using safe defaults and disallowing insecure configurations where possible.

The non-goals of Redox
----------------------

We are not a Linux clone, or POSIX-compliant, nor are we crazy scientists, who wishes to redesign everything. Generally, we stick to the well-tested and proven correct designs. If it ain't broken don't fix it.

This means that a large number of standard programs and libraries will be compatible with Redox. Some things that do not align with our design decisions will have to be ported.

The key here is the trade off between correctness and compatibility. Ideally, you should be able achieve both, but unfortunately, you can't always do so.
