hello world
С����ѧϰ���ӻ���ʱ�򣬽Ӵ���git����������дһ�¹���GitHub���й�֪ʶ��д�����Ŀ�Ļ��ǹ����Լ���ѧϰ��һ�����������Լ�����һ�����ͷ��һ�£���ʲô�����εĶ����������ټ�¼��

����˵һ�°汾����������������������ܹ����㴦�ڿ���״̬����Ŀ�Ŀ��գ��޸���Ŀ����ʵ���¹��ܣ��������Ŀ�����������У����Իָ���ǰһ������״̬��

ͨ��ʹ�ð汾���ƣ����ǿ����������ǵĸĽ���Ŀ�����õ�����Ŀ��Ϊ���Ƿ�����⵽�ƻ������ڴ�����Ŀ��˵�����Ե���Ϊ��Ҫ�����Ƕ���С��Ŀ��˵������ֻ����һ���ļ��ĳ���Ҳ�������档

GibHub������Դ��Git��Git��һ���ֲ�ʽ�汾����ϵͳ���ó���Ա�Ŷ��ܹ�Э��������Ŀ��Git������ҹ���Ϊ��Ŀ�����Ĺ���������һ�����������޸�Ӱ���������������޸ġ�������Ŀ��ʵ��һ���¹��ܵ�ʱ��Git���������ÿ���ļ��������޸ġ�ȷ��������к��㽫�ύ�������޸ģ���Git����¼��Ŀ���µ�״̬������㷸�˴��볷���������޸ģ������ɵķ�����ǰ���κο���״̬��GitHub�ϵ���Ŀ���洢�ڲֿ��У����߰�������Ŀ�������һ�У����룬��Ŀ�����ߵ���Ϣ�������bug�����

���潲һ�°�װGit��С����windowsϵͳ����ֻ��ʾwindowsϵͳ�İ�װ��
Git ��������
Git �Ĺ������Ǵ����ͱ�������Ŀ�Ŀ��ռ���֮��Ŀ��ս��жԱȡ����½����йش������ύ�����Ŀ���յ����������ܡ�
��ȡ�봴����Ŀ����

git init
�� git init ��Ŀ¼�д����µ� Git �ֿ⡣ ��������κ�ʱ���κ�Ŀ¼����ô������ȫ�Ǳ��ػ��ġ�
��Ŀ¼��ִ�� git init���Ϳ��Դ���һ�� Git �ֿ��ˡ��������Ǵ��� runoob ��Ŀ��
?
1
2
3
4
5
$ mkdir runoob
$ cd runoob/
$ git init
Initialized empty Git repository in /Users/tianqixin/www/runoob/.git/
# �� /www/runoob/.git/ Ŀ¼��ʼ���� Git �ֿ����<br>
��������Կ����������Ŀ�������� .git �����Ŀ¼�� �������� Git �ֿ��ˣ������й���Ĵ���Ŀ�Ŀ������ݶ���������
ls -a
. .. .git
git clone
ʹ�� git clone ����һ�� Git �ֿ⵽���أ����Լ��ܹ��鿴����Ŀ�����߽����޸ġ�
�������Ҫ�����˺���һ����Ŀ��������Ҫ����һ����Ŀ���������룬��Ϳ��Կ�¡�Ǹ���Ŀ�� ִ�����
 git clone [url]
[url] Ϊ����Ҫ���Ƶ���Ŀ���Ϳ����ˡ�
�������ǿ�¡ Github �ϵ���Ŀ��
?
1
2
3
4
5
6
7
$ git clone git@github.com:schacon/simplegit.git
Cloning into 'simplegit'...
remote: Counting objects: 13, done.
remote: Total 13 (delta 0), reused 0 (delta 0), pack-reused 13
Receiving objects: 100% (13/13), done.
Resolving deltas: 100% (2/2), done.
Checking connectivity... done.
��¡��ɺ��ڵ�ǰĿ¼�»�����һ�� simplegit Ŀ¼
$ cd simplegit/ $ ls README Rakefile lib
�������������Ƹ���Ŀ��ȫ����¼��
?
1
2
3
4
5
6
7
$ ls -a
.    ..    .git   README  Rakefile lib
$ cd .git
$ ls
HEAD    description info    packed-refs
branches  hooks    logs    refs
config   index    objects
Ĭ������£�Git �ᰴ�����ṩ�� URL ��ָʾ����Ŀ�����ƴ�����ı�����ĿĿ¼�� ͨ�����Ǹ� URL ���һ�� / ֮�����Ŀ���ơ��������Ҫһ����һ�������֣� ������ڸ�������������Ҫ�����ơ�
��������
Git �Ĺ������Ǵ����ͱ��������Ŀ�Ŀ��ռ���֮��Ŀ��ս��жԱȡ����½����йش������ύ�����Ŀ�Ŀ��յ����������ܡ�
git add
git add ����ɽ����ļ���ӵ����棬������������������ļ���
?
1
2
3
4
5
6
7
8
$ touch README
$ touch hello.php
$ ls
README hello.php
$ git status -s
?? README
?? hello.php
$ git add README hello.php 
����������ִ�� git status���Ϳ��Կ����������ļ��Ѿ�����ȥ�ˡ�
?
1
2
3
4
$ git status -s
A README
A hello.php
$ 
����Ŀ�У���������ļ����ձ飬���ǿ���ʹ�� git add . ��������ӵ�ǰ��Ŀ�������ļ���
���������޸� README �ļ���
?
1
2
3
4
5
6
7
$ vim README
<pre>
<p>�� README ����������ݣ�<b># Runoob Git ����</b>��Ȼ�󱣴��˳���</p>
<p>��ִ��һ�� git status��</p>
$ git status -s
AM README
A hello.php
"AM" ״̬����˼�ǣ�����ļ������ǽ�����ӵ�����֮�����иĶ����Ķ���������ִ�� git add �������ӵ������У�
?
1
2
3
4
$ git add .
$ git status -s
A README
A hello.php
����Ҫ������޸İ����ڼ����ύ�Ŀ������ʱ����Ҫִ�� git add��
$ 
git status �������ڲ鿴��Ŀ�ĵ�ǰ״̬��
����������ִ�� git add ����������ļ���
git status
git status �Բ鿴�����ϴ��ύ֮���Ƿ����޸ġ�
����ʾ�������ʱ����� -s �������Ի�ü�̵Ľ����������û�Ӹò�������ϸ������ݣ�
?
1
2
3
4
5
6
7
8
9
10
$ git status
On branch master
 
Initial commit
 
Changes to be committed:
 (use "git rm --cached <file>..." to unstage)
 
 new file:  README
 new file:  hello.php
git diff
ִ�� git diff ���鿴ִ�� git status �Ľ������ϸ��Ϣ��
git diff ������ʾ��д�뻺�������޸ĵ���δд�뻺��ĸĶ�������git diff ��������Ҫ��Ӧ�ó�����
��δ����ĸĶ���git diff
�鿴�ѻ���ĸĶ��� git diff --cached
�鿴�ѻ������δ��������иĶ���git diff HEAD
��ʾժҪ�������� diff��git diff --stat
�� hello.php �ļ��������������ݣ�
?
1
2
3
<?php
echo '����̳̣�www.runoob.com';
?>
?
1
2
3
4
5
6
7
8
9
10
11
12
$ git status -s
A README
AM hello.php
$ git diff
diff --git a/hello.php b/hello.php
index e69de29..69b5711 100644
--- a/hello.php
+++ b/hello.php
@@ -0,0 +1,3 @@
+<?php
+echo '����̳̣�www.runoob.com';
+?>
git status ��ʾ���ϴ��ύ���º�ĸ��Ļ���д�뻺��ĸĶ��� �� git diff һ��һ�е���ʾ��Щ�Ķ�������ɶ��

�������������鿴�� git diff --cached ��ִ��Ч����
?
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
$ git add hello.php 
$ git status -s
A README
A hello.php
$ git diff --cached
diff --git a/README b/README
new file mode 100644
index 0000000..8f87495
--- /dev/null
+++ b/README
@@ -0,0 +1 @@
+# Runoob Git ����
diff --git a/hello.php b/hello.php
new file mode 100644
index 0000000..69b5711
--- /dev/null
+++ b/hello.php
@@ -0,0 +1,3 @@
+<?php
+echo '����̳̣�www.runoob.com';

git commit
ʹ�� git add �����Ҫ���յ�����д�뻺������ ��ִ�� git commit ��������������ӵ��ֿ��С�
Git Ϊ���ÿһ���ύ����¼�����������������ַ�����Ե�һ����Ҫ�����û����������ַ��
$ git config --global user.name 'runoob'
$ git config --global user.email test@runoob.com
����������д�뻺�棬���ύ�� hello.php �����иĶ������׸������У�����ʹ�� -m ѡ���������������ṩ�ύע�͡�
?
1
2
3
4
5
6
7
8
9
$ git add hello.php
$ git status -s
A README
A hello.php
$ $ git commit -m '��һ�ΰ汾�ύ'
[master (root-commit) d32cf1f] ��һ�ΰ汾�ύ
 2 files changed, 4 insertions(+)
 create mode 100644 README
 create mode 100644 hello.php
 ���������Ѿ���¼�˿��ա����������ִ�� git status:
$ git status
# On branch master
nothing to commit (working directory clean)

�������˵�����������һ���ύ֮��û�����κθĶ�����һ��"working directory clean���ɾ��Ĺ���Ŀ¼"��
�����û������ -m ѡ�Git �᳢��Ϊ���һ���༭������д�ύ��Ϣ�� ��� Git ����������������Ҳ��������Ϣ��Ĭ�ϻ�� vim����Ļ����������
?
1
2
3
4
5
6
7
8
9
10
11
# Please enter the commit message for your changes. Lines starting
# with '#' will be ignored, and an empty message aborts the commit.
# On branch master
# Changes to be committed:
#  (use "git reset HEAD <file>..." to unstage)
#
# modified:  hello.php
#
~
~
".git/COMMIT_EDITMSG" 9L, 257C
�������� git add �ύ���������̫��������Git Ҳ�������� -a ѡ��������һ���������ʽ���£�
git commit -a
�������޸� hello.php �ļ�Ϊ�������ݣ�
?
1
2
3
4
<?php
echo '����̳̣�www.runoob.com';
echo '����̳̣�www.runoob.com';
?>
��ִ���������
?
1
2
3
git commit -am '�޸� hello.php �ļ�'
[master 71ee2cb] �޸� hello.php �ļ�
 1 file changed, 1 insertion(+)

git commit -a
�������޸� hello.php �ļ�Ϊ�������ݣ�
?
1
2
3
4
<?php
echo '����̳̣�www.runoob.com';
echo '����̳̣�www.runoob.com';
?>
��ִ���������
?
1
2
3
git commit -am '�޸� hello.php �ļ�'
[master 71ee2cb] �޸� hello.php �ļ�
 1 file changed, 1 insertion(+)
git reset HEAD
git reset HEAD ��������ȡ���ѻ�������ݡ�
�����ȸĶ��ļ� README �ļ����������£�
# Runoob Git ����
# ����̳� 
hello.php �ļ��޸�Ϊ��
?
1
2
3
4
5
<?php
echo '����̳̣�www.runoob.com';
echo '����̳̣�www.runoob.com';
echo '����̳̣�www.runoob.com';
?>

���������ļ��޸ĺ󣬶��ύ���˻���������������Ҫȡ������һ���Ļ��棬�������£�
?
1
2
3
4
5
6
7
8
9
10
11
12
13
$ git status -s
 M README
 M hello.php
$ git add .
$ git status -s
M README
M hello.pp
$ git reset HEAD -- hello.php 
Unstaged changes after reset:
M hello.php
$ git status -s
M README
 M hello.php

������ִ�� git commit��ֻ�Ὣ README �ļ��ĸĶ��ύ���� hello.php ��û�еġ�
?
1
2
3
4
5
$ git commit -m '�޸�'
[master f50cfda] �޸�
 1 file changed, 1 insertion(+)
$ git status -s
 M hello.php
���Կ��� hello.php �ļ����޸Ĳ�Ϊ�ύ��
��ʱ���ǿ���ʹ��������� hello.php ���޸��ύ��
?
1
2
3
4
5
6
$ git commit -am '�޸� hello.php �ļ�'
[master 760f74d] �޸� hello.php �ļ�
 1 file changed, 1 insertion(+)
$ git status
On branch master
nothing to commit, working directory clean
�����֮��ִ�� git reset HEAD ��ȡ��֮ǰ git add ��ӣ�����ϣ����������һ�ύ�����еĻ��档
git rm
git rm �Ὣ��Ŀ�ӻ��������Ƴ������� git reset HEAD ����Ŀȡ��������������ġ� "ȡ������"����˼���ǽ��������ָ�Ϊ���������޸�֮ǰ�����ӡ�
Ĭ������£�git rm file �Ὣ�ļ��ӻ����������Ӳ���У�����Ŀ¼��ɾ����
�����Ҫ�ڹ���Ŀ¼�����Ÿ��ļ�������ʹ�� git rm --cached��
������ɾ�� hello.php�ļ���
?
1
2
3
4
$ git rm hello.php 
rm 'hello.php'
$ ls
README

���ӹ�������ɾ���ļ���
?
1
2
3
4
$ git rm --cached README 
rm 'README'
$ ls
README
git mv
git mv ������������������� git rm --cached ����Ĳ����� �����������ϵ��ļ���Ȼ����ִ�� git add �����ļ���ӵ���������
�����ȰѸ��Ƴ��� README ��ӻ�����
$ git add README 
Ȼ���������:
?
1
2
3
$ git mv README README.md
$ ls
README.md