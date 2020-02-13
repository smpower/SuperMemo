# 备份（Backup）

经常备份数据资料可在数据损坏时方便的恢复。在 SuperMemo 中，有两种方式可以对数据进行备份操作。

## 复制式备份（Copy Collection）[^1]

SuperMemo 的复制式备份是指将指定的集合（collection）复制到本地其他位置，也可以将副本上传至 web 服务器或 ftp 服务器或任意网络位置。假设现有名为 *Physics* 的集合，使用复制式备份（*File: Copy Collection*）时，SuperMemo 默认将其命名为*Physics (copy)*，此时点击 *OK* 按钮或按下 *Enter* 键，将会在 *Physics* 集合所在目录（通常是 *C:\SuperMemo\systems* 目录下）创建一个名为 *Physics (copy).Kno* 的文件和一个 *Physic (Copy)* 文件夹。

一般情况下，备份数据不使用这种方式。当我们要在另一台计算机上使用集合时，会优先选择这种方式——将集合复制到 U 盘，到另一台计算机使用。

## 常规备份（Backup）

这种方式是 SuperMemo 常用的备份手段，备份后的数据默认放在程序根目录的 *backup* 文件夹内，当数据损坏时可以从备份列表中恢复到任意节点。

通过快捷键 *Shift+F12* 或选择主菜单下的 *File: Backup* 进行备份操作。在弹出的 *Choices* 弹框中，默认选择 *Back up at the above location* 选项，点击下方 *OK* 按钮，程序会将备份数据保存在 SuperMemo 程序根目录下的 *backup* 目录中。若要自定义备份位置，选择 *Change the backup location* 选项，在弹出的 *浏览文件夹* 弹框中选择其他备份位置，确定后回到 *Choices* 弹框，点击下方 *OK* 按钮完成备份。

要取消备份，可选中 *Quit* 选项后点击 *OK* 按钮，或直接点击弹框下方的 *Cancel* 按钮以取消备份操作。

----

[^1]: SuperMemo 程序有 4 个级别，分别是 *Beginner*、*Basic*、*Middle* 和 *Professional*，选择复制式备份时需要程序级别在 *Basic* 及以上方可，可在主菜单的 *File: Level* 下选择对应级别。关于程序级别的介绍请查阅[**这里**](/basic/level.html)。
