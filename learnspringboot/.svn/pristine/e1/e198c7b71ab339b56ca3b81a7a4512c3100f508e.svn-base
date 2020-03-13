package com.monkey1024.crud.mapper;

import com.monkey1024.crud.bean.Student;
import org.apache.ibatis.annotations.Mapper;

import java.util.List;
@Mapper
public interface StudentMapper {

    List<Student> selectAllStudent();

    Student selectStudentById(Integer id);

    void addStudent(Student student);

    void updateStudent(Student student);

    void deleteStudent(Integer id);
}
