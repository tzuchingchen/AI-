*
```
ksu@ksu:~/TensorFlow_Code/chapter1$ ls
first_session_only_tensorflow.py  programming_model.py
first_session.py                  using_tensorboard.py
ksu@ksu:~/TensorFlow_Code/chapter1$ python2 first_session_only_tensorflow.py
WARNING:tensorflow:From /usr/local/lib/python2.7/dist-packages/tensorflow/python/util/tf_should_use.py:170: initialize_all_variables (from tensorflow.python.ops.variables) is deprecated and will be removed after 2017-03-02.
Instructions for updating:
Use `tf.global_variables_initializer` instead.
2018-10-03 10:25:07.961891: W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use SSE4.1 instructions, but these are available on your machine and could speed up CPU computations.
2018-10-03 10:25:07.961971: W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use SSE4.2 instructions, but these are available on your machine and could speed up CPU computations.
2018-10-03 10:25:07.962006: W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use AVX instructions, but these are available on your machine and could speed up CPU computations.
2018-10-03 10:25:07.962038: W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use AVX2 instructions, but these are available on your machine and could speed up CPU computations.
10
ksu@ksu:~/TensorFlow_Code/chapter1$ ^C
ksu@ksu:~/TensorFlow_Code/chapter1$ 

```
python2 first_session_only_tensorflow.py
```
```
ksu@ksu:~$ cd TensorFlow_Code
ksu@ksu:~/TensorFlow_Code$ ls 
chapter1  chapter2  chapter3  chapter4  chapter5
ksu@ksu:~/TensorFlow_Code$ cd chapter1
ksu@ksu:~/TensorFlow_Code/chapter1$ ls
first_session_only_tensorflow.py  programming_model.py
first_session.py                  using_tensorboard.py
ksu@ksu:~/TensorFlow_Code/chapter1$ python2 first_session_only_tensorflow.py
2018-10-03 10:40:55.395980: W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use SSE4.1 instructions, but these are available on your machine and could speed up CPU computations.
2018-10-03 10:40:55.396010: W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use SSE4.2 instructions, but these are available on your machine and could speed up CPU computations.
2018-10-03 10:40:55.396015: W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use AVX instructions, but these are available on your machine and could speed up CPU computations.
2018-10-03 10:40:55.396019: W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use AVX2 instructions, but these are available on your machine and could speed up CPU computations.
10

```
