Repo
====
/*
 * To change this template, choose Tools | Templates
 * and open the template in the editor.
 */
package Beans;

import java.util.ArrayList;
import java.sql.Blob;

/**
 *
 * @author Win 7
 */
public class Account {

    private String username;
    private String password;
    private String fname;
    private String email;
    private String birthdate;
    private String gender;
    private int acctNo;
    private char middleI;
    private String achievement;
    private String lname;
    private String picture;
    private String dateRegistered;

    public Account(String username, String password, String fname, String email, String birthdate, String gender, int acctNo, char middleI, String achievement, String lname, String picture, String dateRegistered) {
        this.username = username;
        this.password = password;
        this.fname = fname;
        this.email = email;
        this.birthdate = birthdate;
        this.gender = gender;
        this.acctNo = acctNo;
        this.middleI = middleI;
        this.achievement = achievement;
        this.lname = lname;
        this.picture = picture;
        this.dateRegistered = dateRegistered;
    }


    public Account() {
    }
    
    
    

    public String getDateRegistered() {
        return dateRegistered;
    }

    public void setDateRegistered(String dateRegistered) {
        this.dateRegistered = dateRegistered;
    }

    public void setPicture(String picture) {
        this.picture = picture;
    }

    public String getPicture() {
        return picture;
    }


    public String getGender() {
        return gender;
    }

    public void setGender(String gender) {
        this.gender = gender;
    }

    public void setAchievement(String achievement) {
        this.achievement = achievement;
    }

    public String getAchievement() {
        return achievement;
    }

    public String getBirthdate() {
        return birthdate;
    }

    public void setBirthdate(String birthdate) {
        this.birthdate = birthdate;
    }

    public String getEmail() {
        return email;
    }

    public void setEmail(String email) {
        this.email = email;
    }

    public int getAcctNo() {
        return acctNo;
    }

    public void setAcctNo(int acctNo) {
        this.acctNo = acctNo;
    }

    public String getFname() {
        return fname;
    }

    public String getLname() {
        return lname;
    }

    public char getMiddleI() {
        return middleI;
    }

    public String getPassword() {
        return password;
    }

    public String getUsername() {
        return username;
    }

    public void setFname(String fname) {
        this.fname = fname;
    }

    public void setLname(String lname) {
        this.lname = lname;
    }

    public void setMiddleI(char middleI) {
        this.middleI = middleI;
    }

    public void setPassword(String password) {
        this.password = password;
    }

    public void setUsername(String username) {
        this.username = username;
    }
}
