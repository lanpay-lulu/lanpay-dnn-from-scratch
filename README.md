# Code samples for "Neural Networks and Deep Learning"

## Reference
This project refers to [mnielsen](https://github.com/mnielsen/neural-networks-and-deep-learning).

此代码以mnielsen大神的教程示例代码为基础，做了如下扩展：
- 对dnn的层级做了抽象，包括layer层，output层；
- 对activation函数和cost函数做了抽象，可以很方便的自定义和替换；
- 实现了tanh的激励函数，实现了softmax+极大似然的损失函数；
- 实现了sgd中对batch做矩阵操作；
- 实现了batch normalization；

##License
MIT License

Copyright (c) 2012-2015 Michael Nielsen

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
