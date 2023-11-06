<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.rdbms.server" id="_wdWFIHyDEe6F_fnQESD-eA" name="bdd" md:ref="resource.md#UUID_MD_RDBMS_ORACLE?fileId=UUID_MD_RDBMS_ORACLE$type=md$name=Oracle?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.rdbms.server.module" id="_wd9wMHyDEe6F_fnQESD-eA" value="Oracle"/>
  <attribute defType="com.stambia.rdbms.server.user" id="_-y6xoHyFEe6F_fnQESD-eA" value="CSG1_ORA4"/>
  <attribute defType="com.stambia.rdbms.server.driver" id="_-y6xoXyFEe6F_fnQESD-eA" value="oracle.jdbc.OracleDriver"/>
  <attribute defType="com.stambia.rdbms.server.designerAutoCommit" id="_-y6xonyFEe6F_fnQESD-eA" value="true"/>
  <attribute defType="com.stambia.rdbms.server.password" id="_-y6xo3yFEe6F_fnQESD-eA" value="E887CA1CF8D875D88B286A9B0DB0D6F1"/>
  <attribute defType="com.stambia.rdbms.server.url" id="_-y6xpHyFEe6F_fnQESD-eA" value="jdbc:oracle:thin:@//195.83.93.26:1521/SIAD_PDB2"/>
  <node defType="com.stambia.rdbms.schema" id="_Amy08HyEEe6F_fnQESD-eA" name="CSG1_ORA4">
    <attribute defType="com.stambia.rdbms.schema.name" id="_AnCskHyEEe6F_fnQESD-eA" value="CSG1_ORA4"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_AnDToHyEEe6F_fnQESD-eA" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_AnD6sHyEEe6F_fnQESD-eA" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_AnD6sXyEEe6F_fnQESD-eA" value="I_[targetName]"/>
    <node defType="com.stambia.rdbms.datastore" id="__8g28XyFEe6F_fnQESD-eA" name="SAS_COMPTE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="__8g28nyFEe6F_fnQESD-eA" value="SAS_COMPTE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="__8g283yFEe6F_fnQESD-eA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_ABNJsHyGEe6F_fnQESD-eA" name="CLE_COMPTE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_ABNJsXyGEe6F_fnQESD-eA" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ABNJsnyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ABNJs3yGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ABNJtHyGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ABNJtXyGEe6F_fnQESD-eA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ABNwwHyGEe6F_fnQESD-eA" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_ABNwwXyGEe6F_fnQESD-eA" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ABNwwnyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ABNww3yGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ABNwxHyGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ABNwxXyGEe6F_fnQESD-eA" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ABNwxnyGEe6F_fnQESD-eA" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_ABNwx3yGEe6F_fnQESD-eA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ABNwyHyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ABNwyXyGEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ABNwynyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ABNwy3yGEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ABNwzHyGEe6F_fnQESD-eA" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ABOX0HyGEe6F_fnQESD-eA" name="TYPE" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_ABOX0XyGEe6F_fnQESD-eA" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ABOX0nyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ABOX03yGEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ABOX1HyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ABOX1XyGEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ABOX1nyGEe6F_fnQESD-eA" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ABOX13yGEe6F_fnQESD-eA" name="CABINET" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_ABOX2HyGEe6F_fnQESD-eA" value="CABINET"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ABOX2XyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ABOX2nyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ABOX23yGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ABOX3HyGEe6F_fnQESD-eA" value="9"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ABOX3XyGEe6F_fnQESD-eA" name="DATE_CREATION" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_ABOX3nyGEe6F_fnQESD-eA" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ABOX33yGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ABOX4HyGEe6F_fnQESD-eA" value="6"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ABO-4HyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ABO-4XyGEe6F_fnQESD-eA" value="TIMESTAMP"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ABO-4nyGEe6F_fnQESD-eA" value="11"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ABO-43yGEe6F_fnQESD-eA" name="ID_SOURCE" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_ABO-5HyGEe6F_fnQESD-eA" value="ID_SOURCE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ABO-5XyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ABO-5nyGEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ABO-53yGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ABO-6HyGEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ABO-6XyGEe6F_fnQESD-eA" value="3"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_AN0CUXyGEe6F_fnQESD-eA" name="SAS_EMAIL">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_AN0CUnyGEe6F_fnQESD-eA" value="SAS_EMAIL"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_AN0CU3yGEe6F_fnQESD-eA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_AS26YHyGEe6F_fnQESD-eA" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_AS3hcHyGEe6F_fnQESD-eA" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AS3hcXyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AS3hcnyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AS3hc3yGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AS3hdHyGEe6F_fnQESD-eA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AS3hdXyGEe6F_fnQESD-eA" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_AS3hdnyGEe6F_fnQESD-eA" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AS3hd3yGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AS3heHyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AS3heXyGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AS3henyGEe6F_fnQESD-eA" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AS4IgHyGEe6F_fnQESD-eA" name="EMAIL" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_AS4IgXyGEe6F_fnQESD-eA" value="EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AS4IgnyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AS4Ig3yGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AS4IhHyGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AS4IhXyGEe6F_fnQESD-eA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AS4IhnyGEe6F_fnQESD-eA" name="STATUS" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_AS4Ih3yGEe6F_fnQESD-eA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AS4IiHyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_AS4IiXyGEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AS4IinyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AS4Ii3yGEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AS4IjHyGEe6F_fnQESD-eA" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AS4IjXyGEe6F_fnQESD-eA" name="DATE_CREATION" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_AS4IjnyGEe6F_fnQESD-eA" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AS4Ij3yGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_AS4IkHyGEe6F_fnQESD-eA" value="6"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AS4IkXyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AS4IknyGEe6F_fnQESD-eA" value="TIMESTAMP"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AS4Ik3yGEe6F_fnQESD-eA" value="11"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AS4vkHyGEe6F_fnQESD-eA" name="ID_SOURCE" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_AS4vkXyGEe6F_fnQESD-eA" value="ID_SOURCE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AS4vknyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_AS4vk3yGEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AS4vlHyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AS4vlXyGEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AS4vlnyGEe6F_fnQESD-eA" value="3"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="__1qBAXyFEe6F_fnQESD-eA" name="SAS_CLIENT">
      <attribute defType="com.stambia.rdbms.datastore.name" id="__1qBAnyFEe6F_fnQESD-eA" value="SAS_CLIENT"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="__1qoEHyFEe6F_fnQESD-eA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="__7m4AHyFEe6F_fnQESD-eA" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="__7m4AXyFEe6F_fnQESD-eA" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="__7m4AnyFEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="__7m4A3yFEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="__7m4BHyFEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="__7m4BXyFEe6F_fnQESD-eA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="__7nfEHyFEe6F_fnQESD-eA" name="CLE_COMPTE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="__7nfEXyFEe6F_fnQESD-eA" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="__7nfEnyFEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="__7nfE3yFEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="__7nfFHyFEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="__7nfFXyFEe6F_fnQESD-eA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="__7nfFnyFEe6F_fnQESD-eA" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="__7nfF3yFEe6F_fnQESD-eA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="__7nfGHyFEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="__7nfGXyFEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="__7nfGnyFEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="__7nfG3yFEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="__7nfHHyFEe6F_fnQESD-eA" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="__7oGIHyFEe6F_fnQESD-eA" name="TYPE" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="__7oGIXyFEe6F_fnQESD-eA" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="__7oGInyFEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="__7oGI3yFEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="__7oGJHyFEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="__7oGJXyFEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="__7oGJnyFEe6F_fnQESD-eA" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="__7oGJ3yFEe6F_fnQESD-eA" name="CIVILITE" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="__7oGKHyFEe6F_fnQESD-eA" value="CIVILITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="__7oGKXyFEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="__7oGKnyFEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="__7oGK3yFEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="__7oGLHyFEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="__7oGLXyFEe6F_fnQESD-eA" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="__7oGLnyFEe6F_fnQESD-eA" name="PRENOM" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="__7oGL3yFEe6F_fnQESD-eA" value="PRENOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="__7oGMHyFEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="__7oGMXyFEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="__7oGMnyFEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="__7oGM3yFEe6F_fnQESD-eA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="__7otMHyFEe6F_fnQESD-eA" name="NOM" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="__7otMXyFEe6F_fnQESD-eA" value="NOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="__7otMnyFEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="__7otM3yFEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="__7otNHyFEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="__7otNXyFEe6F_fnQESD-eA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="__7otNnyFEe6F_fnQESD-eA" name="DATE_ANNIVERSAIRE" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="__7otN3yFEe6F_fnQESD-eA" value="DATE_ANNIVERSAIRE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="__7otOHyFEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="__7otOXyFEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="__7otOnyFEe6F_fnQESD-eA" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="__7otO3yFEe6F_fnQESD-eA" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="__7pUQHyFEe6F_fnQESD-eA" name="SEXE" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="__7pUQXyFEe6F_fnQESD-eA" value="SEXE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="__7pUQnyFEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="__7pUQ3yFEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="__7pURHyFEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="__7pURXyFEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="__7pURnyFEe6F_fnQESD-eA" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="__7pUR3yFEe6F_fnQESD-eA" name="MUTUELLE" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="__7pUSHyFEe6F_fnQESD-eA" value="MUTUELLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="__7pUSXyFEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="__7pUSnyFEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="__7pUS3yFEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="__7pUTHyFEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="__7pUTXyFEe6F_fnQESD-eA" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="__7pUTnyFEe6F_fnQESD-eA" name="DATE_CREATION" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="__7pUT3yFEe6F_fnQESD-eA" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="__7pUUHyFEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="__7pUUXyFEe6F_fnQESD-eA" value="6"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="__7pUUnyFEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="__7pUU3yFEe6F_fnQESD-eA" value="TIMESTAMP"/>
        <attribute defType="com.stambia.rdbms.column.size" id="__7pUVHyFEe6F_fnQESD-eA" value="11"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="__7p7UHyFEe6F_fnQESD-eA" name="ID_SOURCE" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="__7p7UXyFEe6F_fnQESD-eA" value="ID_SOURCE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="__7p7UnyFEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="__7p7U3yFEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="__7p7VHyFEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="__7p7VXyFEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="__7p7VnyFEe6F_fnQESD-eA" value="3"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_AHAPsXyGEe6F_fnQESD-eA" name="SAS_ADRESSE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_AHA2wHyGEe6F_fnQESD-eA" value="SAS_ADRESSE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_AHA2wXyGEe6F_fnQESD-eA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_ANTE8HyGEe6F_fnQESD-eA" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_ANTE8XyGEe6F_fnQESD-eA" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ANTE8nyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ANTE83yGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ANTE9HyGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ANTE9XyGEe6F_fnQESD-eA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ANTsAHyGEe6F_fnQESD-eA" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_ANTsAXyGEe6F_fnQESD-eA" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ANTsAnyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ANTsA3yGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ANTsBHyGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ANTsBXyGEe6F_fnQESD-eA" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ANUTEHyGEe6F_fnQESD-eA" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_ANUTEXyGEe6F_fnQESD-eA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ANUTEnyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ANUTE3yGEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ANUTFHyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ANU6IHyGEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ANU6IXyGEe6F_fnQESD-eA" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ANU6InyGEe6F_fnQESD-eA" name="LIGNE_1" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_ANU6I3yGEe6F_fnQESD-eA" value="LIGNE_1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ANU6JHyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ANU6JXyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ANU6JnyGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ANU6J3yGEe6F_fnQESD-eA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ANWIQHyGEe6F_fnQESD-eA" name="LIGNE_2" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_ANWIQXyGEe6F_fnQESD-eA" value="LIGNE_2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ANWIQnyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ANWIQ3yGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ANWIRHyGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ANWIRXyGEe6F_fnQESD-eA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ANWIRnyGEe6F_fnQESD-eA" name="LIGNE_3" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_ANWIR3yGEe6F_fnQESD-eA" value="LIGNE_3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ANWISHyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ANWISXyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ANWISnyGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ANWIS3yGEe6F_fnQESD-eA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ANWvUHyGEe6F_fnQESD-eA" name="LIGNE_4" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_ANWvUXyGEe6F_fnQESD-eA" value="LIGNE_4"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ANWvUnyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ANWvU3yGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ANWvVHyGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ANWvVXyGEe6F_fnQESD-eA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ANWvVnyGEe6F_fnQESD-eA" name="LIGNE_5" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_ANXWYHyGEe6F_fnQESD-eA" value="LIGNE_5"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ANXWYXyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ANXWYnyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ANXWY3yGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ANXWZHyGEe6F_fnQESD-eA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ANXWZXyGEe6F_fnQESD-eA" name="VILLE" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_ANXWZnyGEe6F_fnQESD-eA" value="VILLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ANXWZ3yGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ANXWaHyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ANXWaXyGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ANXWanyGEe6F_fnQESD-eA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ANXWa3yGEe6F_fnQESD-eA" name="CODE_POSTAL" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_ANXWbHyGEe6F_fnQESD-eA" value="CODE_POSTAL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ANXWbXyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ANX9cHyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ANX9cXyGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ANX9cnyGEe6F_fnQESD-eA" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ANX9c3yGEe6F_fnQESD-eA" name="PAYS" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_ANX9dHyGEe6F_fnQESD-eA" value="PAYS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ANX9dXyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ANX9dnyGEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ANX9d3yGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ANX9eHyGEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ANX9eXyGEe6F_fnQESD-eA" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ANYkgHyGEe6F_fnQESD-eA" name="QUALITE" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_ANYkgXyGEe6F_fnQESD-eA" value="QUALITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ANYkgnyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ANYkg3yGEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ANYkhHyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ANYkhXyGEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ANYkhnyGEe6F_fnQESD-eA" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ANYkh3yGEe6F_fnQESD-eA" name="DATE_CREATION" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_ANYkiHyGEe6F_fnQESD-eA" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ANYkiXyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ANYkinyGEe6F_fnQESD-eA" value="6"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ANYki3yGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ANYkjHyGEe6F_fnQESD-eA" value="TIMESTAMP"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ANYkjXyGEe6F_fnQESD-eA" value="11"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ANZLkHyGEe6F_fnQESD-eA" name="ID_SOURCE" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_ANZLkXyGEe6F_fnQESD-eA" value="ID_SOURCE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ANZLknyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ANZLk3yGEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ANZLlHyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ANZLlXyGEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ANZLlnyGEe6F_fnQESD-eA" value="3"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_-zvRAXyFEe6F_fnQESD-eA" name="SAS_SOURCE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_-zv4EHyFEe6F_fnQESD-eA" value="SAS_SOURCE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_-zwfIHyFEe6F_fnQESD-eA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="__nIc0HyFEe6F_fnQESD-eA" name="ID_SOURCE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="__nJD4HyFEe6F_fnQESD-eA" value="ID_SOURCE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="__nJD4XyFEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="__nJD4nyFEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="__nJD43yFEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="__nJD5HyFEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="__nJD5XyFEe6F_fnQESD-eA" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="__nJD5nyFEe6F_fnQESD-eA" name="SOURCE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="__nJq8HyFEe6F_fnQESD-eA" value="SOURCE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="__nJq8XyFEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="__nJq8nyFEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="__nJq83yFEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="__nJq9HyFEe6F_fnQESD-eA" value="200"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_ABpOkXyGEe6F_fnQESD-eA" name="SAS_TELEPHONE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_ABpOknyGEe6F_fnQESD-eA" value="SAS_TELEPHONE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_ABpOk3yGEe6F_fnQESD-eA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_AGkK0HyGEe6F_fnQESD-eA" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_AGkK0XyGEe6F_fnQESD-eA" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AGkK0nyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AGkK03yGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AGkK1HyGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AGkK1XyGEe6F_fnQESD-eA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AGkx4HyGEe6F_fnQESD-eA" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_AGkx4XyGEe6F_fnQESD-eA" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AGkx4nyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AGkx43yGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AGkx5HyGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AGkx5XyGEe6F_fnQESD-eA" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AGkx5nyGEe6F_fnQESD-eA" name="PHONE" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_AGkx53yGEe6F_fnQESD-eA" value="PHONE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AGkx6HyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AGlY8HyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AGlY8XyGEe6F_fnQESD-eA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AGlY8nyGEe6F_fnQESD-eA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AGlY83yGEe6F_fnQESD-eA" name="STATUS" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_AGlY9HyGEe6F_fnQESD-eA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AGlY9XyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_AGlY9nyGEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AGlY93yGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AGlY-HyGEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AGlY-XyGEe6F_fnQESD-eA" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AGlY-nyGEe6F_fnQESD-eA" name="FAVORI" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_AGlY-3yGEe6F_fnQESD-eA" value="FAVORI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AGlY_HyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_AGlY_XyGEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AGlY_nyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AGlY_3yGEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AGlZAHyGEe6F_fnQESD-eA" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AGmAAHyGEe6F_fnQESD-eA" name="TYPE" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_AGmAAXyGEe6F_fnQESD-eA" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AGmAAnyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_AGmAA3yGEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AGmABHyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AGmABXyGEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AGmABnyGEe6F_fnQESD-eA" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AGmAB3yGEe6F_fnQESD-eA" name="DATE_CREATION" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_AGmnEHyGEe6F_fnQESD-eA" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AGmnEXyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_AGmnEnyGEe6F_fnQESD-eA" value="6"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AGmnE3yGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AGmnFHyGEe6F_fnQESD-eA" value="TIMESTAMP"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AGmnFXyGEe6F_fnQESD-eA" value="11"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AGmnFnyGEe6F_fnQESD-eA" name="ID_SOURCE" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_AGmnF3yGEe6F_fnQESD-eA" value="ID_SOURCE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AGmnGHyGEe6F_fnQESD-eA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_AGmnGXyGEe6F_fnQESD-eA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AGmnGnyGEe6F_fnQESD-eA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AGmnG3yGEe6F_fnQESD-eA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AGmnHHyGEe6F_fnQESD-eA" value="3"/>
      </node>
    </node>
  </node>
</md:node>