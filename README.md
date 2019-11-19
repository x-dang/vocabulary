# 我的生词本


## 来自 [*The Rust Programming Language*](https://github.com/rust-lang/book.git)


### convention [kənˈvenʃn]

    n. 大会；[法] 惯例；[计] 约定；[法] 协定；习俗

We’ll discuss them in the context of Rust and explain the **conventions** around using these
concepts.


### nudge [nʌdʒ]; concurrency [kən'kʌrənsi]

    nudge:
    v. （用肘）轻推；轻撞；推开；往前挤；劝说；接近
    n. 推动；（用肘）轻推；触发；激起；说服

    concurrency:
    n. [计] 并发性；同时发生

This is one of many **nudges** Rust gives you to write your code in a way that takes advantage of
the safety and easy **concurrency** that Rust offers.


### illustrate [ˈɪləstreɪt]

    vi. 举例
    vt. 阐明，举例说明；图解

To **illustrate** this, let’s generate a new project called variables in your projects directory by
using `cargo new variables`.


### frustrate [ˈfrʌstreɪt]

    vt. 挫败；阻挠；使感到灰心
    adj. 挫败的；无益的
    vi. 失败；受挫

Even though compiler errors can be **frustrating**, they only mean your program isn’t safely doing
what you want it to do yet.


### assign [əˈsaɪn]

    vt. 分配；指派；[计][数] 赋值
    vi. 将财产过户（尤指过户给债权人）

Cannot **assign** twice to immutable variable.


### designate [ˈdezɪɡneɪt]

    vt. 指定；指派；标出；把…定名为
    adj. 指定的；选定的

It’s important that we get compile-time errors when we attempt to change a value that we previously
**designated** as immutable because this very situation can lead to bugs.


### convey [kənˈveɪ]

    vt. 传达；运输；让与

`mut` **conveys** intent to future readers of the code by indicating that other parts of the code
will be changing this variable’s value.


### penalty [ˈpenəlti]; clarity [ˈklærəti]

    penalty:
    n. 罚款，罚金；处罚

    clarity:
    n. 清楚，明晰；透明

So lower performance might be a worthwhile **penalty** for gaining that **clarity**.


### infer [ɪnˈfɜːr]

    vi. 推断；作出推论
    vt. 推断；推论

The compiler can usually **infer** what type we want to use based on the value and how we use it.


### pervasive [pərˈveɪsɪv]

    adj. 普遍的；到处渗透的；流行的

Functions are **pervasive** in Rust code.


### concrete [ˈkɑːnkriːt]

    n. 具体物；凝结物
    adj. 混凝土的；实在的，具体的；有形的
    vt. 使凝固；用混凝土修筑
    vi. 凝结

When a function has parameters, you can provide it with **concrete** values for those parameters.


### deliberate [dɪˈlɪbərət]

    adj. 故意的；深思熟虑的；从容的
    vt. 仔细考虑；商议

This is a **deliberate** decision in Rust’s design.


### strive [straɪv]; warrant [ˈwɔːrənt]

    strive:
    vi. 努力；奋斗；抗争

    warrant:
    n. 根据；证明；正当理由；委任状
    vt. 保证；担保；批准；辩解

All programmers **strive** to make their code easy to understand, but sometimes extra explanation
is **warranted**.


### concise [kənˈsaɪs]

    adj. 简明的，简洁的

As a more **concise** alternative, you can use a `for` loop and execute some code for each item in
a collection.


### constantly [ˈkɑːnstəntli]

    adv. 不断地；时常地

Some languages have garbage collection that **constantly** looks for no longer used memory as the
program runs.


### boilerplate [ˈbɔɪlərpleɪt]

    n. 样板文件；引用

As a result, our examples will be a bit more concise, letting us focus on the actual details rather
than **boilerplate** code.


### vulnerability [ˌvʌlnərəˈbɪləti]

    n. 易损性；弱点

Freeing memory twice can lead to memory corruption, which can potentially lead to security
**vulnerabilities**.


### scenario [səˈnærioʊ]

    n. 方案；情节；剧本；设想

The `Option` type is used in many places because it encodes the very common **scenario** in which a
value could be something or it could be nothing


### exhaustive [ɪɡˈzɔːstɪv]

    adj. 详尽的；彻底的；消耗的

Matches in Rust are **exhaustive**: we must exhaust every last possibility in order for the code to
be valid.
