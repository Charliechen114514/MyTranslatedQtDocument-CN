# QStack Class

template < typename T> class QStack

QStack类是一个提供堆栈的模板类。[更多的...](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QStack>                                           |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Core) target_link_libraries(mytarget PRIVATE Qt6::Core) |
| qmake:    | QT += core                                                   |
| Inherits: | [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qstack-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QStack 是[隐式共享类](https://doc-qt-io.translate.goog/qt-6/shared.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

**注意：**该类中的所有函数都是[reentrant](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 公共方法

| T         | **[pop](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pop)**() |
| --------- | ------------------------------------------------------------ |
| void      | **[push](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#push)**(const T &*t*) |
| void      | **[swap](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#swap)**(QStack<T> &*other*) |
| T &       | **[top](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#top)**() |
| const T & | **[top](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#top-1)**() const |

## 详细说明

QStack<T> 是 Qt 的泛型之一[container classes](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。它为相同类型的项目实现堆栈数据结构。

堆栈是后进先出 (LIFO) 结构。使用以下命令将项目添加到堆栈顶部[push](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#push)() 并使用从顶部检索[pop](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pop)()。这[top](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#top)() 函数提供对最顶层项目的访问，而无需删除它。

例子：

```
    QStack<int> stack;
    stack.push(1);
    stack.push(2);
    stack.push(3);
    while (!stack.isEmpty())
        cout << stack.pop() << Qt::endl;
```

该示例将按顺序输出 3、2、1。

QStack继承自[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。所有的[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的功能也适用于QStack。例如，您可以使用[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)() 测试栈是否为空，可以使用以下方式遍历QStack[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的迭代器类（例如，[QListIterator](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。但除此之外，QStack 还提供了三个方便的函数，可以轻松实现 LIFO 语义：[push](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#push)(),[pop](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pop)（）， 和[top](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#top)()。

QStack 的值类型必须是[assignable data type](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#assignable-data-type)。这涵盖了大多数常用的数据类型，但是编译器不允许您存储例如[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)作为一个值；相反，存储一个[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)*。

**也可以看看**[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QQueue](https://doc-qt-io.translate.goog/qt-6/qqueue.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员函数文档

### T QStack::pop()

从堆栈中删除顶部项目并将其返回。该函数假设堆栈不为空。

**也可以看看**[top](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#top)(),[push](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#push)（）， 和[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)()。

### void QStack::push(const T &*t*)

添加元素*t*到堆栈的顶部。

这与[QList::append](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)()。

**也可以看看**[pop](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pop)（） 和[top](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#top)()。

### void QStack::swap([QStack](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T> &*other*)

掉期堆栈*other*有了这个堆栈。这个操作非常快并且永远不会失败。

### T &QStack::top()

返回对堆栈顶部项目的引用。该函数假设堆栈不为空。

这与[QList::last](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)()。

**也可以看看**[pop](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pop)(),[push](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#push)（）， 和[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)()。

### const T &QStack::top() const

这是一个重载功能。

**也可以看看**[pop](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pop)（） 和[push](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#push)()。