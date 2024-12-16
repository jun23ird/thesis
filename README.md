# thesis
\include의 문제점은 nesting 이 불가능한 것이다. 그렇다면 파일 시스템을 어떻게 정리할 것인지가 문제가 된다.

우선 root 폴더가 있어야 한다. root 폴더 안에는 main latex파일이 있고 이는 모든것을 취합한다.
root폴더 안에 intro 폴더가 있고 여기에는 summary, introduction,background material이 들어있는 intro latex 파일이 있다. 
root폴더 안에 1st part 폴더가 있고 여기에는 완성된 latex파일들이 들어있다
root폴더 안에 2nd part 폴더가 있고 여기에 각 렘마들의 폴더가 들어 있어야 한다. 이때 \softinclude 사용하고 페이지 브레이크 안 일어나는지 확인.

주의) main latex file에는 1st part는 통째로 include하고 2nd part는 각lemma별로 include한다(이때 \softinclude 사용하고 페이지 브레이크 안 일어나는지 확인).

=========================================================================

2nd part순서
1.natural_alternating_diagrams
2.local_systems_on_as_diagrams
3.lemma1
4.lemma2
5.lemma3
6.lemma4
7.definition5
8.lemma5
9.definition6
10.lemma6
11.definition7
12.lemma7
13.definition8
14.lemma8
15.definition9
16.lemma9
17.definition10
18.lemma10
19.definition11
20.lemma11
21.definition12
22.theorem12
23.definition13
24.theorem13
25.definition14-1
26.definition14-2
27.definition14-3
28.theorem14
29.theorem15

![image](https://github.com/user-attachments/assets/1b43e721-5ba8-4ff9-84e4-b630f0876790)
