1.
接口名：getTeacherInfo
接口功能：查教师基础资料
url：
请求方式：get
传入参数：tno（教师编号）
返回值：{}//教师表中对应的所有字段

2.
接口名：getPermission
接口功能：返回教师权限
url：
请求方式：get
传入参数：tno, rank, subject（教师编号, 年级, 科目）
返回值：{}//返回权限表中相应教师年级科目的权限字段

3.
接口名：addClass
接口功能：教师新建班级
url：
请求方式：post
传入参数：tno（教师编号）
返回值：无

4.
接口名：getStudentByClass
接口功能：对该教师的学生按班级分组
url：
请求方式：get
传入参数：tno（教师编号）
返回值：{} //返回所有学生，并按班级分组

5.
接口名：getAllScore
接口功能：返回该教师所有学生某单元的成绩
url：
请求方式：get
传入参数：rank, subject, unit（rank，subject，unit）
返回值：{} //score表中对应的一条score

6.
接口名：setStudentScore
接口功能：录入学生一个单元的成绩
url：
请求方式：post
传入参数：sno, rank, subject, unit, score（学生编号，rank，subject，unit，成绩）
返回值：无

7.
接口名：getStudentComment
接口功能：返回学生的所有评语
url：
请求方式：get
传入参数：sno（学生编号）
返回值：{}

8.
接口名：setStudentComment
接口功能：录入学生一个单元的评语
url：
请求方式：post
传入参数：sno, rank, subject, unit（学生编号，rank，subject，unit）
返回值：无