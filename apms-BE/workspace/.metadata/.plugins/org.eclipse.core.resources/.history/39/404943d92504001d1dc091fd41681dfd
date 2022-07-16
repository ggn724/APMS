package com.apms.home.mapper;

import java.util.List;

import org.apache.ibatis.annotations.Mapper;

import com.apms.home.vo.UserVO;

@Mapper
public interface UserMapper {
	
	List<UserVO> userList();
	
    UserVO fetchUserByID(int id);
    
    void updateUser(UserVO user);
    
    void insertUser(UserVO user);
    
    void deleteUser(int id);

}
