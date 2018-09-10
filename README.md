测试冲突用4

# Python 资源大全中文版 

我想很多程序员应该记得 GitHub 上有一个 Awesome - XXX 系列的资源整理。[awesome-python](https://github.com/vinta/awesome-python) 是 vinta 发起维护的 Python 资源列表，内容包括：Web 框架、网络爬虫、网络内容提取、模板引擎、数据库、数据可视化、图片处理、文本处理、自然语言处理、机器学习、日志、代码分析等。由伯乐在线持续更新。

Awesome 系列虽然挺全，但基本只对收录的资源做了极为简要的介绍，如果有更详细的中文介绍，对相应开发者的帮助会更大。这也是我们发起这个开源项目的初衷。


## 关于项目

### 我们要做什么？

- 基于 awesome-python 列表，我们将对其中的各个资源项进行编译整理。此外还将从其他来源补充好资源。
- 整理后的内容，将收录在[伯乐在线资源频道](http://hao.jobbole.com/)。可参考已整理的内容：
  - 《[Scrapy：Python 的爬虫框架](http://hao.jobbole.com/python-scrapy/)》
  - 《[Flask：一个使用 Python 编写的轻量级 Web 应用框架](http://hao.jobbole.com/flask/)》


### 如何为列表贡献新资源？

欢迎大家为列表贡献高质量的新资源，提交 PR 时请参照以下要求：

* 请确保推荐的资源自己使用过
* 提交 PR 时请注明推荐理由

资源列表管理收到 PR 请求后，会定期（每周）在微博转发本周提交的 PR 列表，并在微博上面听取使用过这些资源的意见。确认通过后，会加入资源大全。

感谢您的贡献！


### 本项目的参与者

- 维护者：
- 贡献者：[艾凌风](https://github.com/hanxiaomax)、Namco、[Daetalus](https://github.com/Daetalus)、[黄利民](http://www.jobbole.com/members/huanglimin/)、[atupal](http://www.jobbole.com/members/atupal/)、[rainbow](http://www.jobbole.com/members/rainbow/)、[木头lbj](https://github.com/mutoulbj)、[beyondwu](http://www.jobbole.com/members/beyondwu/)、[cissoid](https://github.com/cissoid)、[李广胜](https://github.com/liguangsheng)、[polyval](https://github.com/polyval)、[冰斌](http://www.jobbole.com/members/libing1209/)、[赵叶宇](http://www.jobbole.com/members/nelsonzhao/)、[л stalgic](http://www.jobbole.com/members/fengfeng19910805/)、[硕恩](http://www.jobbole.com/members/shawnw/)、[strongit](https://github.com/strongit)、[yuukilp](http://www.jobbole.com/members/yuukilp/)、[chenjiandongx](https://github.com/chenjiandongx)、[autopenguin](https://github.com/autopenguin)、[visonforcoding](https://github.com/visonforcoding)、[Super赛亚人](https://github.com/No-96)、[Since-future](https://github.com/Since-future)、[knktc](https://github.com/knktc)

注：名单不分排名，不定期补充更新


## 资源列表

### 环境管理

管理 Python 版本和环境的工具

*   p：非常简单的交互式 python 版本管理工具。[官网](https://github.com/qw3rtman/p)
*   pyenv：简单的 Python 版本管理工具。[官网](https://github.com/yyuu/pyenv)
*   Vex：可以在虚拟环境中执行命令。[官网](https://github.com/sashahart/vex)
*   virtualenv：创建独立 Python 环境的工具。[官网](https://pypi.python.org/pypi/virtualenv)
*   virtualenvwrapper：virtualenv 的一组扩展。[官网](https://pypi.python.org/pypi/virtualenvwrapper)

### 包管理

管理包和依赖的工具。

*   pip：Python 包和依赖关系管理工具。[官网](https://pip.pypa.io/)
*   pip-tools：保证 Python 包依赖关系更新的一组工具。[官网](https://github.com/nvie/pip-tools)
*   pipenv：Pyhton 官方推荐的新一代包管理工具。[官网](https://github.com/pypa/pipenv)
*   conda：跨平台，Python 二进制包管理工具。[官网](https://github.com/conda/conda/)
*   Curdling：管理 Python 包的命令行工具。[官网](http://clarete.li/curdling/)
*   wheel：Python 分发的新标准，意在取代 eggs。[官网](http://pythonwheels.com/)

### 包仓库

本地 PyPI 仓库服务和代理。

*   [warehouse](https://pypi.org/)：下一代 PyPI。[官网](https://github.com/pypa/warehouse)
*   bandersnatch：PyPA 提供的 PyPI 镜像工具。[官网](https://bitbucket.org/pypa/bandersnatch)
*   devpi：PyPI 服务和打包/测试/分发工具。[官网](http://doc.devpi.net/)
*   localshop：本地 PyPI 服务（自定义包并且自动对 PyPI 镜像）。[官网](https://github.com/mvantellingen/localshop)

### 分发

打包为可执行文件以便分发。

*   PyInstaller：将 Python 程序转换成独立的执行文件（跨平台）。[官网](https://github.com/pyinstaller/pyinstaller)
*   dh-virtualenv：构建并将 virtualenv 虚拟环境作为一个 Debian 包来发布。[官网](http://dh-virtualenv.readthedocs.org/)
*   Nuitka：将脚本、模块、包编译成可执行文件或扩展模块。[官网](http://nuitka.net/)
*   py2app：将 Python 脚本变为独立软件包（Mac OS X）。[官网](http://pythonhosted.org/py2app/)
*   py2exe：将 Python 脚本变为独立软件包（Windows）。[官网](http://www.py2exe.org/)
*   pynsist：一个用来创建 Windows 安装程序的工具，可以在安装程序中打包 Python 本身。[官网](http://pynsist.readthedocs.org/)

### 构建工具

将源码编译成软件。

*   buildout：一个构建系统，从多个组件来创建，组装和部署应用。[官网](http://www.buildout.org/)
*   BitBake：针对嵌入式 Linux 的类似 make 的构建工具。[官网](http://www.yoctoproject.org/docs/1.6/bitbake-user-manual/bitbake-user-manual.html)
*   fabricate：对任何语言自动找到依赖关系的构建工具。[官网](https://code.google.com/archive/p/fabricate)
*   PlatformIO：多平台命令行构建工具。[官网](https://github.com/platformio/platformio)
*   PyBuilder：纯 Python 实现的持续化构建工具。[官网](https://github.com/pybuilder/pybuilder)
*   SCons：软件构建工具。[官网](http://www.scons.org/)

### 交互式解析器

交互式 Python 解析器。

*   IPython：功能丰富的工具，非常有效的使用交互式 Python。[官网](https://github.com/ipython/ipython)
*   [bpython](http://hao.jobbole.com/bpython/)：界面丰富的 Python 解析器。[官网](http://bpython-interpreter.org/)
*   ptpython：高级交互式 Python 解析器， 构建于 [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) 之上。[官网](https://github.com/jonathanslenders/ptpython)

### 文件

文件管理和 MIME（多用途的网际邮件扩充协议）类型检测。

*   aiofiles：基于 asyncio，提供文件异步操作。[官网](https://github.com/Tinche/aiofiles)
*   imghdr：（Python 标准库）检测图片类型。[官网](https://docs.python.org/2/library/imghdr.html)
*   mimetypes：（Python 标准库）将文件名映射为 MIME 类型。[官网](https://docs.python.org/2/library/mimetypes.html)
*   path.py：对 os.path 进行封装的模块。[官网](https://github.com/jaraco/path.py)
*   pathlib：（Python3.4+ 标准库）跨平台的、面向对象的路径操作库。[官网](https://pathlib.readthedocs.org/en/pep428/)
*   python-magic：文件类型检测的第三方库 libmagic 的 Python 接口。[官网](https://github.com/ahupp/python-magic)
*   Unipath：用面向对象的方式操作文件和目录。[官网](https://github.com/mikeorr/Unipath)
*   watchdog：管理文件系统事件的 API 和 shell 工具。[官网](https://github.com/gorakhargosh/watchdog)

### 日期和时间

操作日期和时间的类库。

*   arrow：更好的 Python 日期时间操作类库。[官网](https://github.com/crsmithdev/arrow)
*   Chronyk：Python 3 的类库，用于解析手写格式的时间和日期。[官网](https://github.com/KoffeinFlummi/Chronyk)
*   dateutil：Python datetime 模块的扩展。[官网](https://pypi.python.org/pypi/python-dateutil)
*   delorean：解决 Python 中有关日期处理的棘手问题的库。[官网](https://github.com/myusuf3/delorean/)
*   maya：人性化的时间处理库。[官网](https://github.com/kennethreitz/maya)
*   moment：一个用来处理时间和日期的 Python 库。灵感来自于 Moment.js。[官网](https://github.com/zachwill/moment)
*   pendulum：一个比 arrow 更具有明确的，可预测的行为的时间操作库。[官网](https://github.com/sdispater/pendulum)
*   PyTime：一个简单易用的 Python 模块，用于通过字符串来操作日期/时间。[官网](https://github.com/shinux/PyTime)
*   pytz：现代以及历史版本的世界时区定义。将时区数据库引入 Python。[官网](https://launchpad.net/pytz)
*   when.py：提供用户友好的函数来帮助用户进行常用的日期和时间操作。[官网](https://github.com/dirn/When.py)

### 文本处理

用于解析和操作文本的库。

*   通用
    *   [chardet](http://hao.jobbole.com/chardet/)：字符编码检测器，兼容 Python2 和 Python3。[官网](https://github.com/chardet/chardet)
    *   difflib：(Python 标准库)帮助我们进行差异化比较。[官网](https://docs.python.org/2/library/difflib.html)
    *   ftfy：让 Unicode 文本更完整更连贯。[官网](https://github.com/LuminosoInsight/python-ftfy)
    *   fuzzywuzzy：模糊字符串匹配。[官网](https://github.com/seatgeek/fuzzywuzzy)
    *   Levenshtein：快速计算编辑距离以及字符串的相似度。[官网](https://github.com/ztane/python-Levenshtein/)
    *   pangu.py：在中日韩语字符和数字字母之间添加空格。[官网](https://github.com/vinta/pangu.py)
    *   pypinyin：汉字拼音转换工具 Python 版。[官网](https://github.com/mozillazg/python-pinyin)
    *   shortuuid：一个生成器库，用以生成简洁的，明白的，URL 安全的 UUID。[官网](https://github.com/stochastic-technologies/shortuuid)
    *   [simplejson](https://github.com/simplejson/simplejson)：Python 的 JSON 编码、解码器。[官网](https://simplejson.readthedocs.io/en/latest/)
    *   unidecode：Unicode 文本的 ASCII 转换形式 。[官网](https://pypi.python.org/pypi/Unidecode)
    *   uniout：打印可读的字符，而不是转义的字符串。[官网](https://github.com/moskytw/uniout)
    *   xpinyin：一个用于把汉字转换为拼音的库。[官网](https://github.com/lxneng/xpinyin)
    *   yfiglet-figlet：[pyfiglet -figlet](https://github.com/pwaller/pyfiglet) 的 Python 实现。
    *   flashtext: 一个高效的文本查找替换库。[官网](https://github.com/vi3k6i5/flashtext)
*   Slug 化
    *   awesome-slugify：一个 Python slug 化库，可以保持 Unicode。[官网](https://github.com/dimka665/awesome-slugify)
    *   python-slugify：Python slug 化库，可以把 unicode 转化为 ASCII。[官网](https://github.com/un33k/python-slugify)
    *   unicode-slugify：一个 slug 工具，可以生成 unicode slugs ,需要依赖 Django 。[官网](https://github.com/mozilla/unicode-slugify)
*   解析器
    *   phonenumbers：解析，格式化，储存，验证电话号码。[官网](https://github.com/daviddrysdale/python-phonenumbers)
    *   PLY：lex 和 yacc 解析工具的 Python 实现。[官网](http://www.dabeaz.com/ply/)
    *   Pygments：通用语法高亮工具。[官网](http://pygments.org/)
    *   pyparsing：生成通用解析器的框架。[官网](http://pyparsing.wikispaces.com/)
    *   python-nameparser：把一个人名分解为几个独立的部分。[官网](https://github.com/derek73/python-nameparser)
    *   python-user-agents：浏览器 user agent 解析器。[官网](https://github.com/selwin/python-user-agents)
    *   sqlparse：一个无验证的 SQL 解析器。[官网](https://sqlparse.readthedocs.org/en/latest/)

### 特殊文本格式处理

一些用来解析和操作特殊文本格式的库。

*   通用
    *   tablib：一个用来处理中表格数据的模块。[官网](https://github.com/kennethreitz/tablib)
*   Office
    *   Marmir：把输入的 Python 数据结构转换为电子表单。[官网](https://github.com/brianray/mm)
    *   openpyxl：一个用来读写 Excel 2010 xlsx/xlsm/xltx/xltm 文件的库。[官网](https://openpyxl.readthedocs.org/en/latest/)
    *   pyexcel：一个提供统一 API，用来读写，操作 Excel 文件的库。[官网](https://github.com/pyexcel/pyexcel)
    *   python-docx：读取，查询以及修改 Microsoft Word 2007/2008 docx 文件。[官网](https://github.com/python-openxml/python-docx)
    *   relatorio：模板化 OpenDocument 文件。[官网](http://relatorio.tryton.org/)
    *   unoconv：在 LibreOffice/OpenOffice 支持的任意文件格式之间进行转换。[官网](https://github.com/dagwieers/unoconv)
    *   XlsxWriter：一个用于创建 Excel .xlsx 文件的 Python 模块。[官网](https://xlsxwriter.readthedocs.org/en/latest/)
    *   xlwings：一个使得在 Excel 中方便调用 Python 的库（反之亦然），基于 BSD 协议。[官网](http://xlwings.org/)
    *   [xlwt](http://hao.jobbole.com/xlwt/)：读写 Excel 文件的数据和格式信息。[官网](https://github.com/python-excel/xlwt) / [xlrd](https://github.com/python-excel/xlrd)
*   PDF
    *   PDFMiner：一个用于从 PDF 文档中抽取信息的工具。[官网](https://github.com/euske/pdfminer)
    *   PyPDF2：一个可以分割，合并和转换 PDF 页面的库。[官网](https://github.com/mstamy2/PyPDF2)
    *   ReportLab：快速创建富文本 PDF 文档。[官网](http://www.reportlab.com/opensource/)
*   Markdown
    *   Mistune：快速并且功能齐全的纯 Python 实现的 Markdown 解析器。[官网](https://github.com/lepture/mistune)
    *   Python-Markdown：John Gruber’s Markdown 的 Python 版实现。[官网](https://github.com/waylan/Python-Markdown)
    *   Python-Markdown2：纯 Python 实现的 Markdown 解析器，比 Python-Markdown 更快，更准确，可扩展。[官网](https://github.com/trentm/python-markdown2)
*   YAML
    *   PyYAML：Python 版本的 YAML 解析器。[官网](http://pyyaml.org/)
*   CSV
    *   csvkit：用于转换和操作 CSV 的工具。[官网](https://github.com/wireservice/csvkit)
*   Archive
    *   unp：一个用来方便解包归档文件的命令行工具。[官网](https://github.com/mitsuhiko/unp)

### 自然语言处理

用来处理人类语言的库。

*   [NLTK](http://hao.jobbole.com/nltk/)：一个先进的平台，用以构建处理人类语言数据的 Python 程序。[官网](http://www.nltk.org/)
*   jieba：中文分词工具。[官网](https://github.com/fxsjy/jieba)
*   langid.py：独立的语言识别系统。[官网](https://github.com/saffsd/langid.py)
*   Pattern：Python 网络信息挖掘模块。[官网](http://www.clips.ua.ac.be/pattern)
*   SnowNLP：一个用来处理中文文本的库。[官网](https://github.com/isnowfy/snownlp)
*   TextBlob：为进行普通自然语言处理任务提供一致的 API。[官网](http://textblob.readthedocs.org/en/latest/)
*   TextGrocery：一简单高效的短文本分类工具，基于 LibLinear 和 Jieba。[官网](https://github.com/2shou/TextGrocery)
*   thulac:清华大学自然语言处理与社会人文计算实验室研制推出的一套中文词法分析工具包[官网](https://github.com/thunlp/THULAC-Python)

### 文档

用以生成项目文档的库。

*   [Sphinx](http://hao.jobbole.com/sphinx/)：Python 文档生成器。[官网](http://www.sphinx-doc.org/en/latest/)
*   awesome-sphinxdoc：[官网](https://github.com/yoloseem/awesome-sphinxdoc)
*   MkDocs：对 Markdown 友好的文档生成器。[官网](http://www.mkdocs.org/)
*   pdoc：一个可以替换 Epydoc 的库，可以自动生成 Python 库的 API 文档。[官网](https://github.com/BurntSushi/pdoc)
*   Pycco：文学编程（literate-programming）风格的文档生成器。[官网](https://github.com/pycco-docs/pycco)
*   readthedocs：一个基于 Sphinx/MkDocs 的在线文档托管系统，对开源项目免费开放使用。[官网](https://github.com/rtfd/readthedocs.org/)

### 配置

用来保存和解析配置的库。

*   config：[logging](https://docs.python.org/2/library/logging.html) 模块作者写的分级配置模块。[官网](https://www.red-dove.com/config-doc/)
*   ConfigObj：INI 文件解析器，带验证功能。[官网](http://www.voidspace.org.uk/python/configobj.html)
*   ConfigParser：(Python 标准库) INI 文件解析器。[官网](https://docs.python.org/2/library/configparser.html)
*   profig：通过多种格式进行配置，具有数值转换功能。[官网](http://profig.readthedocs.org/en/default/)
*   python-decouple：将设置和代码完全隔离。[官网](https://github.com/henriquebastos/python-decouple)

### 命令行工具

用于创建命令行程序的库。

*   命令行程序开发
    *   asciimatics：跨平台，全屏终端包（即鼠标/键盘输入和彩色，定位文本输出），完整的复杂动画和特殊效果的高级 API。[官网](https://github.com/peterbrittain/asciimatics)
    *   cement：Python 的命令行程序框架。[官网](http://builtoncement.com/)
    *   click：一个通过组合的方式来创建精美命令行界面的包。[官网](http://click.pocoo.org/dev/)
    *   cliff：一个用于创建命令行程序的框架，可以创建具有多层命令的命令行程序。[官网](http://docs.openstack.org/developer/cliff/)
    *   clint：Python 命令行程序工具。[官网](https://github.com/kennethreitz/clint)
    *   colorama：跨平台彩色终端文本。[官网](https://pypi.python.org/pypi/colorama)
    *   docopt：Python 风格的命令行参数解析器。[官网](http://docopt.org/)
    *   Gooey：一条命令，将命令行程序变成一个 GUI 程序。[官网](https://github.com/chriskiehl/Gooey)
    *   python-prompt-toolkit：一个用于构建强大的交互式命令行程序的库。[官网](https://github.com/jonathanslenders/python-prompt-toolkit)
    *   python-fire：Google 出品的一个基于 Python 类的构建命令行界面的库。[官网](https://github.com/google/python-fire)
    *   [Pythonpy](http://hao.jobbole.com/pythonpy/)：在命令行中直接执行任何 Python 指令。[官网](https://github.com/Russell91/pythonpy/wiki)
*   生产力工具
    *   aws-cli：Amazon Web Services 的通用命令行界面。[官网](https://github.com/aws/aws-cli)
    *   bashplotlib：在终端中进行基本绘图。[官网](https://github.com/glamp/bashplotlib)
    *   caniusepython3：判断是哪个项目妨碍你你移植到 Python3。[官网](https://github.com/brettcannon/caniusepython3)
    *   cookiecutter：从 cookiecutters（项目模板）创建项目的一个命令行工具。[官网](https://github.com/audreyr/cookiecutter)
    *   doitlive：一个用来在终端中进行现场演示的工具。[官网](https://github.com/sloria/doitlive)
    *   pyftpdlib：一个速度极快和可扩展的 Python FTP 服务库。[官网](https://github.com/giampaolo/pyftpdlib)
    *   howdoi：通过命令行获取即时的编程问题解答。[官网](https://github.com/gleitz/howdoi)
    *   httpie：一个命令行 HTTP 客户端，cURL 的替代品，易用性更好。[官网](https://github.com/jkbrzt/httpie)
    *   PathPicker：从 bash 输出中选出文件。[官网](https://github.com/facebook/PathPicker)
    *   percol：向 UNIX shell 传统管道概念中加入交互式选择功能。[官网](https://github.com/mooz/percol)
    *   SAWS：一个加强版的 AWS 命令行。[官网](https://github.com/donnemartin/saws)
    *   thefuck：修正你之前的命令行指令。[官网](https://github.com/nvbn/thefuck)
    *   mycli：一个 MySQL 命令行客户端，具有自动补全和语法高亮功能。[官网](https://github.com/dbcli/mycli)
    *   pgcli：Postgres 命令行工具，具有自动补全和语法高亮功能。[官网](https://github.com/dbcli/pgcli)
    *   try：一个从来没有更简单的命令行工具，用来试用 python 库。[官网](https://github.com/timofurrer/try)

### 下载器

用来进行下载的库.

*   s3cmd：一个用来管理 Amazon S3 和 CloudFront 的命令行工具。[官网](https://github.com/s3tools/s3cmd)
*   s4cmd：超级 S3 命令行工具，性能更加强劲。[官网](https://github.com/bloomreach/s4cmd)
*   you-get：一个 YouTube/Youku/Niconico 视频下载器，使用 Python3 编写。[官网](https://www.soimort.org/you-get/)
*   youtube-dl：一个小巧的命令行程序，用来下载 YouTube 视频。[官网](http://rg3.github.io/youtube-dl/)

### 图像处理

用来操作图像的库.

*   [pillow](http://hao.jobbole.com/pillow/)：Pillow 是一个更加易用版的 [PIL](http://www.pythonware.com/products/pil/)。[官网](http://pillow.readthedocs.org/en/latest/)
*   hmap：图像直方图映射。[官网](https://github.com/rossgoodwin/hmap)
*   imgSeek：一个使用视觉相似性搜索一组图片集合的项目。[官网](https://sourceforge.net/projects/imgseek/)
*   nude.py：裸体检测。[官网](https://github.com/hhatto/nude.py)
*   pyBarcode：不借助 PIL 库在 Python 程序中生成条形码。[官网](https://pythonhosted.org/pyBarcode/)
*   pygram：类似 Instagram 的图像滤镜。[官网](https://github.com/ajkumar25/pygram)
*   python-qrcode：一个纯 Python 实现的二维码生成器。[官网](https://github.com/lincolnloop/python-qrcode)
*   Quads：基于四叉树的计算机艺术。[官网](https://github.com/fogleman/Quads)
*   scikit-image：一个用于（科学）图像处理的 Python 库。[官网](http://scikit-image.org/)
*   thumbor：一个小型图像服务，具有剪裁，尺寸重设和翻转功能。[官网](https://github.com/thumbor/thumbor)
*   wand：[MagickWand](http://www.imagemagick.org/script/magick-wand.php)的 Python 绑定。MagickWand 是 ImageMagick 的 C API 。[官网](https://github.com/dahlia/wand)
*   face_recognition：简单易用的 python 人脸识别库。[官网](https://github.com/ageitgey/face_recognition)

### OCR

光学字符识别库。

*   pyocr：Tesseract 和 Cuneiform 的一个封装(wrapper)。[官网](https://github.com/jflesch/pyocr)
*   [pytesseract](http://hao.jobbole.com/pytesseract/)：[Google Tesseract OCR](https://github.com/tesseract-ocr) 的另一个封装(wrapper)。[官网](https://github.com/madmaze/pytesseract)
*   python-tesseract：[Google Tesseract OCR](https://github.com/tesseract-ocr) 的一个包装类。

### 音频

用来操作音频的库

*   audiolazy：Python 的数字信号处理包。[官网](https://github.com/danilobellini/audiolazy) 
*   audioread：交叉库 (GStreamer + Core Audio + MAD + FFmpeg) 音频解码。[官网](https://github.com/beetbox/audioread)
*   beets：一个音乐库管理工具及 [MusicBrainz](https://musicbrainz.org/) 标签添加工具。[官网](http://beets.io/)
*   dejavu：音频指纹提取和识别。[官网](https://github.com/worldveil/dejavu)
*   [django-elastic-transcoder](http://hao.jobbole.com/django-elastic-transcoder/)：Django + [Amazon Elastic Transcoder](http://aws.amazon.com/elastictranscoder/)。[官网](https://github.com/StreetVoice/django-elastic-transcoder)
*   eyeD3：一个用来操作音频文件的工具，具体来讲就是包含 ID3 元信息的 MP3 文件。[官网](http://eyed3.nicfit.net/)
*   id3reader：一个用来读取 MP3 元数据的 Python 模块。[官网](http://nedbatchelder.com/code/modules/id3reader.py)
*   m3u8：一个用来解析 m3u8 文件的模块。[官网](https://github.com/globocom/m3u8)
*   mutagen：一个用来处理音频元数据的 Python 模块。[官网](https://bitbucket.org/lazka/mutagen)
*   pydub：通过简单、简洁的高层接口来操作音频文件。[官网](https://github.com/jiaaro/pydub)
*   pyechonest：[Echo Nest](http://developer.echonest.com/) API 的 Python 客户端。[官网](https://github.com/echonest/pyechonest)
*   talkbox：一个用来处理演讲/信号的 Python 库。[官网](http://scikits.appspot.com/talkbox)
*   TimeSide：开源 web 音频处理框架。[官网](https://github.com/Parisson/TimeSide)
*   tinytag：一个用来读取 MP3, OGG, FLAC 以及 Wave 文件音乐元数据的库。[官网](https://github.com/devsnd/tinytag)
*   mingus：一个高级音乐理论和曲谱包，支持 MIDI 文件和回放功能。[官网](http://bspaans.github.io/python-mingus/)

### Video

用来操作视频和 GIF 的库。

*   moviepy：一个用来进行基于脚本的视频编辑模块，适用于多种格式，包括动图 GIFs。[官网](http://zulko.github.io/moviepy/)
*   scikit-video：SciPy 视频处理常用程序。[官网](https://github.com/aizvorski/scikit-video)

### 地理位置

地理编码地址以及用来处理经纬度的库。

*   GeoDjango：世界级地理图形 web 框架。[官网](https://docs.djangoproject.com/en/dev/ref/contrib/gis/)
*   GeoIP：MaxMind GeoIP Legacy 数据库的 Python API。[官网](https://github.com/maxmind/geoip-api-python)
*   geojson：GeoJSON 的 Python 绑定及工具。[官网](https://github.com/frewsxcv/python-geojson)
*   geopy：Python 地址编码工具箱。[官网](https://github.com/geopy/geopy)
*   pygeoip：纯 Python GeoIP API。[官网](https://github.com/appliedsec/pygeoip)
*   django-countries：一个 Django 应用程序，提供用于表格的国家选择功能，国旗图标静态文件以及模型中的国家字段。[官网](https://github.com/SmileyChris/django-countries)

### HTTP

使用 HTTP 的库。
*   aiohttp：基于 asyncio 的异步 HTTP 网络库。[官网](https://github.com/aio-libs/aiohttp)
*   requests：人性化的 HTTP 请求库。[官网](http://docs.python-requests.org/en/latest/)
*   grequests：requests 库 + gevent ，用于异步 HTTP 请求.[官网](https://github.com/kennethreitz/grequests)
*   httplib2：全面的 HTTP 客户端库。[官网](https://github.com/jcgregorio/httplib2)
*   treq：类似 requests 的 Python API 构建于 Twisted HTTP 客户端之上。[官网](https://github.com/twisted/treq)
*   urllib3：一个具有线程安全连接池，支持文件 post，清晰友好的 HTTP 库。[官网](https://github.com/shazow/urllib3)

### 数据库

Python 实现的数据库。

*   pickleDB：一个简单，轻量级键值储存数据库。[官网](https://pythonhosted.org/pickleDB/)
*   PipelineDB：流式 SQL 数据库。[官网](https://www.pipelinedb.com/)
*   TinyDB：一个微型的，面向文档型数据库。[官网](https://github.com/msiemens/tinydb)
*   ZODB：一个 Python 原生对象数据库。一个键值和对象图数据库。[官网](http://www.zodb.org/en/latest/)

### 数据库驱动

用来连接和操作数据库的库。

*   MySQL：[awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/) 系列
    *   aiomysql：基于 asyncio 的异步 MySQL 数据库操作库。[官网](https://github.com/aio-libs/aiomysql)
    *   mysql-python：Python 的 MySQL 数据库连接器。[官网](https://sourceforge.net/projects/mysql-python/)
    *   ysqlclient：[mysql-python](https://github.com/PyMySQL/mysqlclient-python) 分支，支持 Python 3。
    *   oursql：一个更好的 MySQL 连接器，支持原生预编译指令和 BLOBs。[官网](https://pythonhosted.org/oursql/)
    *   PyMySQL：纯 Python MySQL 驱动，兼容 mysql-python。[官网](https://github.com/PyMySQL/PyMySQL)
*   PostgreSQL
    *   psycopg2：Python 中最流行的 PostgreSQL 适配器。[官网](http://initd.org/psycopg/)
    *   queries：psycopg2 库的封装，用来和 PostgreSQL 进行交互。[官网](https://github.com/gmr/queries)
    *   txpostgres：基于 Twisted 的异步 PostgreSQL 驱动。[官网](http://txpostgres.readthedocs.org/en/latest/)
*   其他关系型数据库
    *   apsw：另一个 Python SQLite 封装。[官网](http://rogerbinns.github.io/apsw/)
    *   dataset：在数据库中存储 Python 字典
    *   pymssql：一个简单的 Microsoft SQL Server 数据库接口。[官网](http://www.pymssql.org/en/latest/)
*   NoSQL 数据库
    *   cassandra-python-driver：Cassandra 的 Python 驱动。[官网](https://github.com/datastax/python-driver)
    *   HappyBase：一个为 Apache HBase 设计的，对开发者友好的库。[官网](http://happybase.readthedocs.org/en/latest/)
    *   Plyvel：一个快速且功能丰富的 LevelDB 的 Python 接口。[官网](https://plyvel.readthedocs.org/en/latest/)
    *   py2neo：Neo4j restful 接口的 Python 封装客户端。[官网](http://py2neo.org/2.0/)
    *   pycassa：Cassandra 的 Python Thrift 驱动。[官网](https://github.com/pycassa/pycassa)
    *   PyMongo：MongoDB 的官方 Python 客户端。[官网](https://docs.mongodb.org/ecosystem/drivers/python/)
    *   redis-py：Redis 的 Python 客户端。[官网](https://github.com/andymccurdy/redis-py)
    *   telephus：基于 Twisted 的 Cassandra 客户端。[官网](https://github.com/driftx/Telephus)
    *   txRedis：基于 Twisted 的 Redis 客户端。[官网](https://github.com/deldotdr/txRedis)

### ORM

实现对象关系映射或数据映射技术的库。

*   关系型数据库
    *   Django Models：Django 的一部分。[官网](https://docs.djangoproject.com/en/dev/topics/db/models/)
    *   SQLAlchemy：Python SQL 工具以及对象关系映射工具。[官网](http://www.sqlalchemy.org/)
        *   [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy) 系列
    *   [Peewee](http://hao.jobbole.com/peewee/)：一个小巧，富有表达力的 ORM。[官网](https://github.com/coleifer/peewee)
    *   PonyORM：提供面向生成器的 SQL 接口的 ORM。[官网](https://ponyorm.com/)
    *   python-sql：编写 Python 风格的 SQL 查询。[官网](https://pypi.python.org/pypi/python-sql)
*   NoSQL 数据库
    *   django-mongodb-engine：Django MongoDB 后端。[官网](https://github.com/django-nonrel/mongodb-engine)
    *   PynamoDB：[Amazon DynamoDB](https://aws.amazon.com/dynamodb/) 的一个 Python 风格接口。[官网](https://github.com/jlafon/PynamoDB)
    *   flywheel：Amazon DynamoDB 的对象映射工具。[官网](https://github.com/mathcamp/flywheel)
    *   MongoEngine：一个 Python 对象文档映射工具，用于 MongoDB。[官网](http://mongoengine.org/)
    *   hot-redis：为 Redis 提供 Python 丰富的数据类型。[官网](https://github.com/stephenmcd/hot-redis)
    *   redisco：一个 Python 库，提供可以持续存在在 Redis 中的简单模型和容器。[官网](https://github.com/kiddouk/redisco)
*   其他
    *   butterdb：Google Drive 电子表格的 Python ORM。[官网](https://github.com/Widdershin/butterdb)

### Web 框架

全栈 Web 框架。

*   [Django](http://hao.jobbole.com/django/)：Python 界最流行的 web 框架。[官网](https://www.djangoproject.com/)
    *   [awesome-django](https://gitlab.com/rosarior/awesome-django) 系列
*   [Flask](http://hao.jobbole.com/flask/)：一个 Python 微型框架。[官网](http://flask.pocoo.org/)
    *   [awesome-flask](https://github.com/humiaozuzu/awesome-flask) 系列
*   pyramid：一个小巧，快速，接地气的开源 Python web 框架。
    *   [awesome-pyramid](https://github.com/uralbash/awesome-pyramid) 系列
*   [Bottle](http://hao.jobbole.com/bottle/)：一个快速小巧，轻量级的 WSGI 微型 web 框架。[官网](http://bottlepy.org/docs/dev/index.html)
*   CherryPy：一个极简的 Python web 框架，服从 HTTP/1.1 协议且具有 WSGI 线程池。[官网](http://www.cherrypy.org/)
*   TurboGears：一个可以扩展为全栈解决方案的微型框架。[官网](http://www.turbogears.org/)
*   [web.py](http://hao.jobbole.com/python-webpy/)：一个 Python 的 web 框架，既简单，又强大。[官网](http://webpy.org/)
*   web2py：一个全栈 web 框架和平台，专注于简单易用。[官网](http://www.web2py.com/)
*   [Tornado](http://hao.jobbole.com/tornado/)：一个 web 框架和异步网络库。[官网](http://www.tornadoweb.org/en/latest/)
*   sanic：基于 Python3.5+ 的异步网络框架。[官网](https://github.com/channelcat/sanic/)

### 权限

允许或拒绝用户访问数据或功能的库。

*   Carteblanche：站在用户和设计者角度开发的一个代码对齐模块，很好地处理了代码导航及权限。[官网](https://github.com/neuman/python-carteblanche/)
*   django-guardian：Django 1.2+ 实现了单个对象权限。[官网](https://github.com/django-guardian/django-guardian)
*   django-rules：一个小巧但是强大的应用，提供对象级别的权限管理，且不需要使用数据库。[官网](https://github.com/dfunckt/django-rules)

### CMS

内容管理系统

*   odoo-cms: 一个开源的，企业级 CMS，基于 odoo。[官网](http://www.odoo.com)
*   django-cms：一个开源的，企业级 CMS，基于 Django。[官网](http://www.django-cms.org/en/)
*   djedi-cms：一个轻量级但却非常强大的 Django CMS ，考虑到了插件，内联编辑以及性能。[官网](http://djedi-cms.org/)
*   FeinCMS：基于 Django 构建的最先进的内容管理系统之一。[官网](http://www.feincms.org/)
*   Kotti：一个高级的，Python 范的 web 应用框架，基于 Pyramid 构建。[官网](http://kotti.pylonsproject.org/)
*   Mezzanine：一个强大的，持续的，灵活的内容管理平台。[官网](http://mezzanine.jupo.org/)
*   Opps：一个为杂志，报纸网站以及大流量门户网站设计的 CMS 平台，基于 Django。[官网](http://opps.github.io/opps/)
*   Plone：一个构建于开源应用服务器 Zope 之上的 CMS。[官网](https://plone.org/)
*   Quokka：灵活，可扩展的小型 CMS，基于 Flask 和 MongoDB。[官网](http://quokkaproject.org/)
*   [Wagtail](http://hao.jobbole.com/wagtail/)：一个 Django 内容管理系统。[官网](https://wagtail.io/)
*   Widgy：最新的 CMS 框架，基于 Django。[官网](https://wid.gy/)

### 电子商务

用于电子商务以及支付的框架和库。

*   django-oscar：一个用于 Django 的开源的电子商务框架。[官网](http://oscarcommerce.com/)
*   django-shop：一个基于 Django 的店铺系统。[官网](https://github.com/awesto/django-shop)
*   Cartridge：一个基于 Mezzanine 构建的购物车应用。[官网](https://github.com/stephenmcd/cartridge)
*   shoop：一个基于 Django 的开源电子商务平台。[官网](https://www.shoop.io/en/)
*   alipay：非官方的 Python 支付宝 API。[官网](https://github.com/lxneng/alipay)
*   merchant：一个可以接收来自多种支付平台支付的 Django 应用。[官网](https://github.com/agiliq/merchant)
*   money：一个货币类库。带有可选的 CLDR 后端本地化格式，提供可扩展的货币兑换解决方案。[官网](https://github.com/carlospalol/money)
*   python-currencies：显示货币格式以及它的数值。[官网](https://github.com/Alir3z4/python-currencies)

### RESTful API

用来开发 RESTful APIs 的库

*   Django
    *   [django-rest-framework](http://hao.jobbole.com/django-rest-framework/)：一个强大灵活的工具，用来构建 web API。[官网](http://www.django-rest-framework.org/)
    *   django-tastypie：为 Django 应用开发 API。[官网](http://tastypieapi.org/)
    *   django-formapi：为 Django 的表单验证，创建 JSON APIs 。[官网](https://github.com/5monkeys/django-formapi)
*   Flask
    *   flask-api：为 flask 开发的，可浏览 Web APIs 。[官网](http://www.flaskapi.org/)
    *   flask-restful：为 flask 快速创建 REST APIs 。[官网](http://flask-restful.readthedocs.org/en/latest/)
    *   flask-restless：为 SQLAlchemy 定义的数据库模型创建 RESTful APIs 。[官网](https://flask-restless.readthedocs.org/en/latest/)
    *   flask-api-utils：为 Flask 处理 API 表示和验证。[官网](https://github.com/marselester/flask-api-utils)
    *   eve：REST API 框架，由 Flask, MongoDB 等驱动。[官网](https://github.com/nicolaiarocci/eve)
*   Pyramid
    *   cornice：一个 Pyramid 的 REST 框架 。[官网](https://cornice.readthedocs.org/en/latest/)
*   与框架无关的
    *   falcon：一个用来建立云 API 和 web app 后端的高性能框架。[官网](http://falconframework.org/)
    *   sandman：为现存的数据库驱动系统自动创建 REST APIs 。[官网](https://github.com/jeffknupp/sandman)
    *   restless：框架无关的 REST 框架 ，基于从 Tastypie 学到的知识。[官网](http://restless.readthedocs.org/en/latest/)
    *   ripozo：快速创建 REST/HATEOAS/Hypermedia APIs。[官网](https://github.com/vertical-knowledge/ripozo)

### 验证

实现验证方案的库。

*   OAuth
    *   Authomatic：简单但是强大的框架，身份验证/授权客户端。[官网](http://peterhudec.github.io/authomatic/)
    *   django-allauth：Django 的验证应用。[官网](https://github.com/pennersr/django-allauth)
    *   django-oauth-toolkit：为 Django 用户准备的 OAuth2。[官网](https://github.com/evonove/django-oauth-toolkit)
    *   django-oauth2-provider：为 Django 应用提供 OAuth2 接入。[官网](https://github.com/caffeinehit/django-oauth2-provider)
    *   Flask-OAuthlib：OAuth 1.0/a, 2.0 客户端实现，供 Flask 使用。[官网](https://github.com/lepture/flask-oauthlib)
    *   OAuthLib：一个 OAuth 请求-签名逻辑通用、 完整的实现。[官网](https://github.com/idan/oauthlib)
    *   python-oauth2：一个完全测试的抽象接口。用来创建 OAuth 客户端和服务端。[官网](https://github.com/joestump/python-oauth2)
    *   python-social-auth：一个设置简单的社会化验证方式。[官网](https://github.com/omab/python-social-auth)
    *   rauth：OAuth 1.0/a, 2.0, 和 Ofly 的 Python 库。[官网](https://github.com/litl/rauth)
    *   sanction：一个超级简单的 OAuth2 客户端实现。[官网](https://github.com/demianbrecht/sanction)
*   其他
    *   jose：JavaScript 对象签名和加密草案的实现。[官网](https://github.com/demonware/jose)
    *   PyJWT：JSON Web 令牌草案 01。[官网](https://github.com/jpadilla/pyjwt)
    *   python-jws：JSON Web 签名草案 02 的实现。[官网](https://github.com/brianloveswords/python-jws)
    *   python-jwt：一个用来生成和验证 JSON Web 令牌的模块。[官网](https://github.com/davedoesdev/python-jwt)

### 模板引擎

模板生成和词法解析的库和工具。

*   [Jinja2](http://hao.jobbole.com/jinja2/)：一个现代的，对设计师友好的模板引擎。[官网](https://github.com/pallets/jinja)
*   Chameleon：一个 HTML/XML 模板引擎。 模仿了 ZPT（Zope Page Templates）, 进行了速度上的优化。[官网](https://chameleon.readthedocs.org/en/latest/)
*   Genshi：Python 模板工具，用以生成 web 感知的结果。[官网](https://genshi.edgewall.org/)
*   Mako：Python 平台的超高速轻量级模板。[官网](http://www.makotemplates.org/)

### 队列

处理事件以及任务队列的库。

*   celery：一个异步任务队列/作业队列，基于分布式消息传递。[官网](http://www.celeryproject.org/)
*   huey：小型多线程任务队列。[官网](https://github.com/coleifer/huey)
*   [mrq](http://hao.jobbole.com/mrq/)：Mr. Queue -一个 Python 的分布式 worker 任务队列， 使用 Redis 和 gevent。[官网](https://github.com/pricingassistant/mrq)
*   rq：简单的 Python 作业队列。[官网](http://python-rq.org/)
*   simpleq：一个简单的，可无限扩张的，基于亚马逊 SQS 的队列。[官网](https://github.com/rdegges/simpleq)

### 搜索

对数据进行索引和执行搜索查询的库和软件。

*   django-haystack：Django 模块化搜索。[官网](https://github.com/django-haystack/django-haystack)
*   elasticsearch-py：Elasticsearch 的官方底层 Python 客户端。[官网](https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html)
*   elasticsearch-dsl-py：Elasticsearch 的官方高级 Python 客户端。[官网](https://github.com/elastic/elasticsearch-dsl-py) 
*   solrpy：[solr](http://lucene.apache.org/solr/) 的 Python 客户端。[官网](https://github.com/edsu/solrpy)
*   Whoosh：一个快速的纯 Python 搜索引擎库。[官网](http://whoosh.readthedocs.org/en/latest/)

### 动态消息

用来创建用户活动的库。

*   django-activity-stream：从你的站点行为中生成通用活动信息流。[官网](https://github.com/justquick/django-activity-stream)
*   Stream-Framework：使用 Cassandra 和 Redis 创建动态消息和通知系统。[官网](https://github.com/tschellenbach/Stream-Framework)

### 资源管理

管理、压缩、缩小网站资源的工具。

*   django-compressor：将链接和内联的 JavaScript 或 CSS 压缩到一个单独的缓存文件中。[官网](https://github.com/django-compressor/django-compressor)
*   django-storages：一个针对 Django 的自定义存储后端的工具集合。[官网](http://django-storages.readthedocs.org/en/latest/)
*   fanstatic：打包、优化，并且把静态文件依赖作为 Python 的包来提供。[官网](http://www.fanstatic.org/en/latest/)
*   File Conveyor：一个后台驻留的程序，用来发现和同步文件到 CDNs, S3 和 FTP。[官网](http://fileconveyor.org/)
*   Flask-Assets：帮你将 web 资源整合到你的 Flask app 中。[官网](http://flask-assets.readthedocs.org/en/latest/)
*   jinja-assets-compressor：一个 Jinja 扩展，用来编译和压缩你的资源。[官网](https://github.com/jaysonsantos/jinja-assets-compressor)
*   webassets：为你的静态资源打包、优化和管理生成独一无二的缓存 URL。[官网](http://webassets.readthedocs.org/en/latest/)

### 缓存

缓存数据的库。

*   Beaker：一个缓存和会话库，可以用在 web 应用和独立 Python 脚本和应用上。[官网](http://beaker.readthedocs.org/en/latest/)
*   django-cache-machine：Django 模型的自动缓存和失效。[官网](https://github.com/django-cache-machine/django-cache-machine)
*   django-cacheops：具有自动颗粒化事件驱动失效功能的 ORM。[官网](https://github.com/Suor/django-cacheops)
*   django-viewlet：渲染模板，同时具有额外的缓存控制功能。[官网](https://github.com/5monkeys/django-viewlet)
*   dogpile.cache：dogpile.cache 是 Beaker 的下一代替代品，由同一作者开发。[官网](http://dogpilecache.readthedocs.org/en/latest/)
*   HermesCache：Python 缓存库，具有基于标签的失效和 dogpile effect 保护功能。[官网](https://pypi.python.org/pypi/HermesCache)
*   johnny-cache：django 应用缓存框架。[官网](https://github.com/jmoiron/johnny-cache)
*   pylibmc：[libmemcached](http://libmemcached.org/libMemcached.html) 接口的 Python 封装。[官网](https://github.com/lericson/pylibmc)

### 电子邮件

用来发送和解析电子邮件的库。

*   django-celery-ses：带有 AWS SES 和 Celery 的 Django email 后端。[官网](https://github.com/StreetVoice/django-celery-ses)
*   envelopes：供人类使用的电子邮件库。[官网](http://tomekwojcik.github.io/envelopes/)
*   flanker：一个 email 地址和 Mime 解析库。[官网](https://github.com/mailgun/flanker)
*   imbox：Python IMAP 库。[官网](https://github.com/martinrusev/imbox)
*   inbox.py：Python SMTP 服务器。[官网](https://github.com/kennethreitz/inbox.py)
*   inbox：一个开源电子邮件工具箱。[官网](https://github.com/nylas/sync-engine)
*   lamson：Python 风格的 SMTP 应用服务器。[官网](https://github.com/zedshaw/lamson)
*   mailjet：Mailjet API 实现，用来提供批量发送邮件，统计等功能。[官网](https://github.com/WoLpH/mailjet)
*   marrow.mailer：高性能可扩展邮件分发框架。[官网](https://github.com/marrow/mailer)
*   modoboa：一个邮件托管和管理平台，具有现代的、简约的 Web UI。[官网](https://github.com/tonioo/modoboa)
*   pyzmail：创建，发送和解析电子邮件。[官网](http://www.magiksys.net/pyzmail/)
*   Talon：Mailgun 库，用来抽取信息和签名。[官网](https://github.com/mailgun/talon)

### 国际化

用来进行国际化的库。

*   Babel：一个 Python 的国际化库。[官网](http://babel.pocoo.org/en/latest/)
*   Korean：一个韩语词态库。[官网](https://korean.readthedocs.org/en/latest/)

### URL 处理

解析 URLs 的库

*   furl：一个让处理 URL 更简单小型 Python 库。[官网](https://github.com/gruns/furl)
*   purl：一个简单的，不可变的 URL 类，具有简洁的 API 来进行询问和处理。[官网](https://github.com/codeinthehole/purl)
*   pyshorteners：一个纯 Python URL 缩短库。[官网](https://github.com/ellisonleao/pyshorteners)
*   shorturl：生成短小 URL 和类似 bit.ly 短链的 Python 实现。[官网](https://github.com/Alir3z4/python-shorturl)
*   webargs：一个解析 HTTP 请求参数的库，内置对流行 web 框架的支持，包括 Flask, Django, Bottle, Tornado 和 Pyramid。[官网](https://github.com/sloria/webargs)

### HTML 处理

处理 HTML 和 XML 的库。

*   BeautifulSoup：以 Python 风格的方式来对 HTML 或 XML 进行迭代，搜索和修改。[官网](http://www.crummy.com/software/BeautifulSoup/bs4/doc/)
*   bleach：一个基于白名单的 HTML 清理和文本链接库。[官网](http://bleach.readthedocs.org/en/latest/)
*   cssutils：一个 Python 的 CSS 库。[官网](https://pypi.python.org/pypi/cssutils/)
*   html5lib：一个兼容标准的 HTML 文档和片段解析及序列化库。[官网](https://github.com/html5lib/html5lib-python)
*   lxml：一个非常快速，简单易用，功能齐全的库，用来处理 HTML 和 XML。[官网](http://lxml.de/)
*   MarkupSafe：为 Python 实现 XML/HTML/XHTML 标记安全字符串。[官网](https://github.com/pallets/markupsafe)
*   pyquery：一个解析 HTML 的库，类似 jQuery。[官网](https://github.com/gawel/pyquery)
*   requests-html：人性化的，Pythonic 的 HTML 解析库。[官网](https://github.com/kennethreitz/requests-html)
*   untangle：将 XML 文档转换为 Python 对象，使其可以方便的访问。[官网](https://github.com/stchris/untangle)
*   xhtml2pdf：HTML/CSS 转 PDF 工具。[官网](https://github.com/xhtml2pdf/xhtml2pdf)
*   xmltodict：像处理 JSON 一样处理 XML。[官网](https://github.com/martinblech/xmltodict)

爬取网络站点的库

*   Scrapy：一个快速高级的屏幕爬取及网页采集框架。[官网](http://scrapy.org/)
*   cola：一个分布式爬虫框架。[官网](https://github.com/chineking/cola)
*   Demiurge：基于 PyQuery 的爬虫微型框架。[官网](https://github.com/matiasb/demiurge)
*   feedparser：通用 feed 解析器。[官网](http://pythonhosted.org/feedparser/)
*   Grab：站点爬取框架。[官网](http://grablib.org/)
*   MechanicalSoup：用于自动和网络站点交互的 Python 库。[官网](https://github.com/hickford/MechanicalSoup)
*   portia：Scrapy 可视化爬取。[官网](https://github.com/scrapinghub/portia)
*   pyspider：一个强大的爬虫系统。[官网](https://github.com/binux/pyspider)
*   RoboBrowser：一个简单的，Python 风格的库，用来浏览网站，而不需要一个独立安装的浏览器。[官网](https://github.com/jmcarp/robobrowser)

### 网页内容提取

用于进行网页内容提取的库。

*   Haul：一个可以扩展的图像爬取工具。[官网](https://github.com/vinta/Haul)
*   html2text：将 HTML 转换为 Markdown 格式文本。[官网](https://github.com/Alir3z4/html2text)
*   lassie：人性化的网页内容检索库。[官网](https://github.com/michaelhelmick/lassie)
*   micawber：一个小型网页内容提取库，用来从 URLs 提取富内容。[官网](https://github.com/coleifer/micawber) 
*   [newspaper](http://hao.jobbole.com/python-newspaper/)：使用 Python 进行新闻提取，文章提取以及内容策展。[官网](https://github.com/codelucas/newspaper)
*   opengraph：一个用来解析开放内容协议(Open Graph Protocol)的 Python 模块。[官网](https://github.com/erikriver/opengraph)
*   [python-goose](http://hao.jobbole.com/python-goose/)：HTML 内容/文章提取器。[官网](https://github.com/grangier/python-goose)
*   python-readability：arc90 公司 readability 工具的 Python 高速端口。[官网](https://github.com/buriy/python-readability)
*   sanitize：为杂乱的数据世界带来调理性。[官网](https://github.com/Alir3z4/python-sanitize)
*   sumy：一个为文本文件和 HTML 页面进行自动摘要的模块。[官网](https://github.com/miso-belica/sumy)
*   textract：从任何格式的文档中提取文本，Word，PowerPoint，PDFs 等等。[官网](https://github.com/deanmalmgren/textract)

### 表单

进行表单操作的库。

*   Deform：Python HTML 表单生成库，受到了 formish 表单生成库的启发。[官网](http://deform.readthedocs.org/en/latest/)
*   django-bootstrap3：集成了 Bootstrap 3 的 Django。[官网](https://github.com/dyve/django-bootstrap3)
*   django-crispy-forms：一个 Django 应用，他可以让你以一种非常优雅且 DRY（Don't repeat yourself） 的方式来创建美观的表单。[官网](http://django-crispy-forms.readthedocs.org/en/latest/)
*   django-remote-forms：一个平台独立的 Django 表单序列化工具。[官网](https://github.com/WiserTogether/django-remote-forms)
*   WTForms：一个灵活的表单验证和呈现库。[官网](http://wtforms.readthedocs.org/en/latest/)
*   WTForms-JSON：一个 WTForms 扩展，用来处理 JSON 数据。[官网](http://wtforms-json.readthedocs.org/en/latest/)

### 数据验证

数据验证库。多用于表单验证。

*   Cerberus：一个映射验证器（mappings-validator）。支持多种规则，提供归一化功能，可以方便地定制为 Python 风格的 schema 定义。[官网](http://docs.python-cerberus.org/en/stable/)
*   colander：一个用于对从 XML, JSON，HTML 表单获取的数据或其他同样简单的序列化数据进行验证和反序列化的系统。[官网](http://docs.pylonsproject.org/projects/colander/en/latest/)
*   kmatch：一种用于匹配/验证/筛选 Python 字典的语言。[官网](https://github.com/ambitioninc/kmatch)
*   schema：一个用于对 Python 数据结构进行验证的库。[官网](https://github.com/keleshev/schema) 
*   Schematics：数据结构验证。[官网](https://github.com/schematics/schematics)
*   valideer：轻量级可扩展的数据验证和适配库。[官网](https://github.com/podio/valideer)
*   voluptuous：一个 Python 数据验证库。主要是为了验证传入 Python 的 JSON，YAML 等数据。[官网](https://github.com/alecthomas/voluptuous)
*   jsonschema：[JSON Schema](http://json-schema.org/)的python实现，用于JSON数据的验证。[官网](https://github.com/Julian/jsonschema)

### 反垃圾技术

帮助你和电子垃圾进行战斗的库。

*   django-simple-captcha：一个简单、高度可定制的 Django 应用，可以为任何 Django 表单添加验证码。[官网](https://github.com/mbi/django-simple-captcha)
*   django-simple-spam-blocker：一个用于 Django 的简单的电子垃圾屏蔽工具。[官网](https://github.com/moqada/django-simple-spam-blocker)

### 标记

用来进行标记的库。

*   django-taggit：简单的 Django 标记工具。[官网](https://github.com/alex
