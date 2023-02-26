## 算法管理

### 1. 算法配置

1. 点击"算法管理——算法配置"，进入算法配置页面，获取当前使用的算法及算法版本。
2. 字段说明
   - 算法模块：算法所属模块。
   - 算法名称：当前算法名称。
   - 算法版本：当前算法使用的版本。
   - 状态：当前算法启用/禁用状态。
   - 修改时间：展示成功修改配置的时间。
3. 编辑
   - 点击“编辑”，可以修改算法版本和禁用启用状态。算法版本为下拉列表，展示当前算法可使用版本，选择版本后，点击确定，可进行版本修改。
4. 配置
   - 若“算法版本或禁用/启用”有更新，点击“配置”后，向后端发送更新请求，若“算法版本或禁用/启用”有更新，但不点击配置，则不发送请求，刷新页面后，算法版本仍为修改前的版本。
5. 算法名称搜索框
   - 输入框，输入算法名称后点击查询，仅展示符合条件的算法。

### 2. 算法版本

点击"算法管理——算法版本"，进入算法版本管理页面，可对系统算法版本进行管理。

#### 2.1 新增算法版本

1. 新增版本
   - 点击“新增”，
   - 在添加页面需录入以下信息：
     - 算法类型：下拉框选择系统设定的算法类型。
     - 算法名称：下拉框选择系统设定的算法名称。
     - 算法版本：输入新增的算法版本名称。
   - 点击“确定”，系统对新增内容进行校验，若内容无误，完成算法版本数据的添加； 若必填字段为空值，则提示“xx 为空，添加失败 ”。
     点击“取消”或“X”，在添加页面录入的信息不保存，回到算法版本列表中。
2. 搜索框：可根据算法版本名称进行搜索。

#### 2.2 算法版本列表

1. 字段说明
   - 算法模块：算法所属模块。
   - 算法名称：当前算法名称。
   - 算法版本：算法名称对应的版本。多个版本时多行显示。
   - 删除：系统自带的算法版本不可删除，删除按钮置灰，用户新增的算法版本可删除，若用户新增的算法版本处于使用状态，删除时提示“当前版本使用中，无法删除”。