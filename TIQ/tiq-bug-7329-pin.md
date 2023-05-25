# Bug 7329 - Pin function does not workable
**solution**

- 1.修改search方法，在queryIndex前添加相关的查询条件。（后端）
- 2.PinPosition接口中，添加refenceId = "Message"+referenceId 方法（后端）
- 3.前端将查询列表的查询条件删除（前端）
- 4.换Pin接口（前端）


- **sortField要用**