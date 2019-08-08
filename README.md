# 4sitesHubbard
[In Japanese] 4サイトフェルミオンハバード模型を色々な手法で解く

様々な手法で4サイトのハーフフィリングのフェルミオンハバード模型を解きます。
プログラミング言語は自由です。
オープンソースな4サイトハバード模型ソルバーを目指しているので、もし「こんな方法もあるぞ」という方はPull requestsで貢献していただけると嬉しいです。

1. 4サイトHubbard模型の厳密対角化

状態を全てあげて対角化します。
https://github.com/cometscome/4sitesHubbard/blob/master/01ExactDiagonalization/Hubbard_exact.ipynb

言語:Julia 1.1

2. 4サイトHubbard模型のHartree Fock近似

Hatree-Fock近似を行なって、その範囲内で最小のエネルギーを持つ状態を探索します。
https://github.com/cometscome/4sitesHubbard/blob/master/02HartreeFock/HartreeFock.ipynb

言語:Julia 1.1

