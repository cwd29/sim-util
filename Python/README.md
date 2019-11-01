#### Python目录结构说明
- docs: 存放说明文件的
  - README.md
- core: 存放核心代码
  - modules：存放自己的类库
    - sim: 自己的类库名
      - sim.py
      - sim_new.py
    - sim_string
      - string.py
      - sim_string.py
  - lib: 存放第三方的库
  - scripts: 自己的普通代码
    - demo: 文件夹名
      - index.py
      - index_demo.py
- tests：测试用例
  - modules: 核心类库
    - sim: 与modules中的类库名一致
      - sim_tests.py
      - sim_new_tests.py
    - sim_string
      - string_tests.py
      - sim_string_tests.py
  -scripts:普通代码测试
    - demo: 与scripts下的文件夹同名
      - index_test.py
      - index_demo_test.py