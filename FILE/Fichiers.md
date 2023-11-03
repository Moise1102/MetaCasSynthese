<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.file.server" id="_FaryAHokEe6cgaTnMFlv7A" name="source" md:ref="resource.md#UUID_TECH_FILE_MD?fileId=UUID_TECH_FILE_MD$type=md$name=File?" internalVersion="v1.0.0">
  <node defType="com.stambia.file.directory" id="_FoPs4HokEe6cgaTnMFlv7A">
    <attribute defType="com.stambia.file.directory.path" id="_FpWgIHokEe6cgaTnMFlv7A" value="C:\source"/>
    <node defType="com.stambia.file.file" id="_gtg3wXopEe6cgaTnMFlv7A" name="F_CLIENT_20231001">
      <attribute defType="com.stambia.file.file.physicalName" id="_l9T9cHopEe6cgaTnMFlv7A" value="F_CLIENT_20231001.txt"/>
      <attribute defType="com.stambia.file.file.type" id="_mQbGsHopEe6cgaTnMFlv7A" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_oUyLIHopEe6cgaTnMFlv7A" value="0"/>
      <attribute defType="com.stambia.file.file.charsetName" id="_puvnsHopEe6cgaTnMFlv7A" value="UTF-8"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_rjLZwHopEe6cgaTnMFlv7A" value="0D0A"/>
      <attribute defType="com.stambia.file.file.header" id="_uw4E0HopEe6cgaTnMFlv7A" value="0"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_wxsGAHopEe6cgaTnMFlv7A" value="2E"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_gN__UHorEe6cgaTnMFlv7A" value="7C"/>
      <attribute defType="com.stambia.file.file.stringDelimiter" id="_Pq1DwHoyEe6cgaTnMFlv7A"/>
      <attribute defType="com.stambia.file.file.escapeChar" id="_Pq1DwXoyEe6cgaTnMFlv7A"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_Pq1DwnoyEe6cgaTnMFlv7A" value="0"/>
      <node defType="com.stambia.file.record" id="_8vN0sXo5Ee6cgaTnMFlv7A" name="ENTETE">
        <node defType="com.stambia.file.filter" id="_BAKFcno6Ee6cgaTnMFlv7A" name="entete">
          <attribute defType="com.stambia.file.filter.value" id="_ERGRwHo6Ee6cgaTnMFlv7A" value="000"/>
          <attribute defType="com.stambia.file.filter.start" id="_EctE0Ho6Ee6cgaTnMFlv7A" value="1"/>
          <attribute defType="com.stambia.file.filter.length" id="_FFzFIHo6Ee6cgaTnMFlv7A" value="3"/>
          <attribute defType="com.stambia.file.filter.operator" id="_FacfcHo6Ee6cgaTnMFlv7A" value="Equals"/>
        </node>
        <node defType="com.stambia.file.field" id="_HNE6sHo6Ee6cgaTnMFlv7A" name="TYPE_LIGNE" position="1">
          <attribute defType="com.stambia.file.field.size" id="_HNE6sXo6Ee6cgaTnMFlv7A" value="3"/>
          <attribute defType="com.stambia.file.field.type" id="_HNE6sno6Ee6cgaTnMFlv7A" value="String"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_HNE6s3o6Ee6cgaTnMFlv7A" value="TYPE_LIGNE"/>
          <attribute defType="com.stambia.file.field.physicalSize" id="_88slIHo7Ee6cgaTnMFlv7A" value="3"/>
        </node>
        <node defType="com.stambia.file.field" id="_HNE6tHo6Ee6cgaTnMFlv7A" name="TYPE_FICHIER" position="2">
          <attribute defType="com.stambia.file.field.size" id="_HNE6tXo6Ee6cgaTnMFlv7A" value="20"/>
          <attribute defType="com.stambia.file.field.type" id="_HNE6tno6Ee6cgaTnMFlv7A" value="String"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_HNE6t3o6Ee6cgaTnMFlv7A" value="TYPE_FICHIER"/>
          <attribute defType="com.stambia.file.field.physicalSize" id="__GUkEHo7Ee6cgaTnMFlv7A" value="20"/>
        </node>
        <node defType="com.stambia.file.field" id="_HNE6uHo6Ee6cgaTnMFlv7A" name="VERSION" position="3">
          <attribute defType="com.stambia.file.field.size" id="_HNE6uXo6Ee6cgaTnMFlv7A" value="2"/>
          <attribute defType="com.stambia.file.field.type" id="_HNE6uno6Ee6cgaTnMFlv7A" value="String"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_HNE6u3o6Ee6cgaTnMFlv7A" value="VERSION"/>
          <attribute defType="com.stambia.file.field.physicalSize" id="_B7ezUHo8Ee6cgaTnMFlv7A" value="2"/>
        </node>
        <node defType="com.stambia.file.field" id="_HNE6xXo6Ee6cgaTnMFlv7A" name="SEQUENCE" position="6">
          <attribute defType="com.stambia.file.field.size" id="_HNE6xno6Ee6cgaTnMFlv7A" value="6"/>
          <attribute defType="com.stambia.file.field.type" id="_HNE6x3o6Ee6cgaTnMFlv7A" value="String"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_HNE6yHo6Ee6cgaTnMFlv7A" value="SEQUENCE"/>
          <attribute defType="com.stambia.file.field.physicalSize" id="_L0tiQHo8Ee6cgaTnMFlv7A" value="6"/>
        </node>
        <node defType="com.stambia.file.field" id="_HNE6wXo6Ee6cgaTnMFlv7A" name="SOURCE" position="5">
          <attribute defType="com.stambia.file.field.size" id="_HNE6wno6Ee6cgaTnMFlv7A" value="30"/>
          <attribute defType="com.stambia.file.field.type" id="_HNE6w3o6Ee6cgaTnMFlv7A" value="String"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_HNE6xHo6Ee6cgaTnMFlv7A" value="SOURCE"/>
          <attribute defType="com.stambia.file.field.physicalSize" id="_HqpVkHo8Ee6cgaTnMFlv7A" value="30"/>
        </node>
        <node defType="com.stambia.file.field" id="_HNE6vHo6Ee6cgaTnMFlv7A" name="DATE" position="4">
          <attribute defType="com.stambia.file.field.size" id="_HNE6vXo6Ee6cgaTnMFlv7A" value="30"/>
          <attribute defType="com.stambia.file.field.type" id="_HNE6vno6Ee6cgaTnMFlv7A" value="String"/>
          <attribute defType="com.stambia.file.field.format" id="_HNE6v3o6Ee6cgaTnMFlv7A" value=""/>
          <attribute defType="com.stambia.file.field.physicalName" id="_HNE6wHo6Ee6cgaTnMFlv7A" value="DATE"/>
          <attribute defType="com.stambia.file.field.physicalSize" id="_EEUIEHo8Ee6cgaTnMFlv7A" value="30"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.file.file" id="_b3q4cHpQEe6QncsbWkl3eg" name="F_CLIENT_20231001">
      <attribute defType="com.stambia.file.file.type" id="_b6tlYHpQEe6QncsbWkl3eg" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.charsetName" id="_b6zsAHpQEe6QncsbWkl3eg"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_b61hMHpQEe6QncsbWkl3eg" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_b62IQHpQEe6QncsbWkl3eg" value="7C"/>
      <attribute defType="com.stambia.file.file.stringDelimiter" id="_b62vUHpQEe6QncsbWkl3eg"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_b639cHpQEe6QncsbWkl3eg" value="2E"/>
      <attribute defType="com.stambia.file.file.escapeChar" id="_b64kgHpQEe6QncsbWkl3eg"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_b65yoHpQEe6QncsbWkl3eg" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_b66ZsHpQEe6QncsbWkl3eg" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_b67n0HpQEe6QncsbWkl3eg" value="0"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_cwunYHpQEe6QncsbWkl3eg" value="F_CLIENT_20231001.txt"/>
      <node defType="com.stambia.file.record" id="_hGKWkXpQEe6QncsbWkl3eg">
        <node defType="com.stambia.file.filter" id="_iOTqYnpQEe6QncsbWkl3eg" name="entete">
          <attribute defType="com.stambia.file.filter.value" id="_jytcYHpQEe6QncsbWkl3eg" value="000"/>
          <attribute defType="com.stambia.file.filter.start" id="_j-xicHpQEe6QncsbWkl3eg" value="1"/>
          <attribute defType="com.stambia.file.filter.length" id="_kWNLAHpQEe6QncsbWkl3eg" value="3"/>
          <attribute defType="com.stambia.file.filter.operator" id="_mPIbgHpQEe6QncsbWkl3eg" value="Equals"/>
        </node>
      </node>
      <node defType="com.stambia.file.field" id="_fTmz0HpQEe6QncsbWkl3eg" name="F1" position="1">
        <attribute defType="com.stambia.file.field.size" id="_fTmz0XpQEe6QncsbWkl3eg" value="12"/>
        <attribute defType="com.stambia.file.field.type" id="_fTna4HpQEe6QncsbWkl3eg" value="Numeric"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_fTna4XpQEe6QncsbWkl3eg" value="F1"/>
      </node>
      <node defType="com.stambia.file.field" id="_fTp3IHpQEe6QncsbWkl3eg" name="F2" position="2">
        <attribute defType="com.stambia.file.field.size" id="_fTp3IXpQEe6QncsbWkl3eg" value="56"/>
        <attribute defType="com.stambia.file.field.type" id="_fTp3InpQEe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_fTp3I3pQEe6QncsbWkl3eg" value="F2"/>
      </node>
      <node defType="com.stambia.file.field" id="_fTp3JHpQEe6QncsbWkl3eg" name="F3" position="3">
        <attribute defType="com.stambia.file.field.size" id="_fTp3JXpQEe6QncsbWkl3eg" value="59"/>
        <attribute defType="com.stambia.file.field.type" id="_fTp3JnpQEe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_fTp3J3pQEe6QncsbWkl3eg" value="F3"/>
      </node>
      <node defType="com.stambia.file.field" id="_fTp3KHpQEe6QncsbWkl3eg" name="F4" position="4">
        <attribute defType="com.stambia.file.field.size" id="_fTp3KXpQEe6QncsbWkl3eg" value="71"/>
        <attribute defType="com.stambia.file.field.type" id="_fTp3KnpQEe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.format" id="_fTp3K3pQEe6QncsbWkl3eg" value="yyyy-MM-dd"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_fTp3LHpQEe6QncsbWkl3eg" value="F4"/>
      </node>
      <node defType="com.stambia.file.field" id="_fTp3LXpQEe6QncsbWkl3eg" name="F5" position="5">
        <attribute defType="com.stambia.file.field.size" id="_fTp3LnpQEe6QncsbWkl3eg" value="54"/>
        <attribute defType="com.stambia.file.field.type" id="_fTp3L3pQEe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_fTp3MHpQEe6QncsbWkl3eg" value="F5"/>
      </node>
      <node defType="com.stambia.file.field" id="_fTp3MXpQEe6QncsbWkl3eg" name="F6" position="6">
        <attribute defType="com.stambia.file.field.size" id="_fTp3MnpQEe6QncsbWkl3eg" value="64"/>
        <attribute defType="com.stambia.file.field.type" id="_fTp3M3pQEe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_fTp3NHpQEe6QncsbWkl3eg" value="F6"/>
      </node>
    </node>
  </node>
  <node defType="com.stambia.file.directory" id="_WWqRgHpREe6QncsbWkl3eg" name="source">
    <attribute defType="com.stambia.file.directory.path" id="_WXn60HpREe6QncsbWkl3eg" value="C:\source"/>
    <node defType="com.stambia.file.file" id="_WXq-IHpREe6QncsbWkl3eg" name="F_CLIENT_20231001">
      <attribute defType="com.stambia.file.file.type" id="_WYYv0HpREe6QncsbWkl3eg" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.charsetName" id="_WYZ98HpREe6QncsbWkl3eg"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_WYalAHpREe6QncsbWkl3eg" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_WYbMEHpREe6QncsbWkl3eg" value="7C"/>
      <attribute defType="com.stambia.file.file.stringDelimiter" id="_WYbMEXpREe6QncsbWkl3eg"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_WYcaMHpREe6QncsbWkl3eg" value="2E"/>
      <attribute defType="com.stambia.file.file.escapeChar" id="_WYcaMXpREe6QncsbWkl3eg"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_WYcaMnpREe6QncsbWkl3eg" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_WYdBQHpREe6QncsbWkl3eg" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_WYdoUHpREe6QncsbWkl3eg" value="0"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_ZPFQIHpREe6QncsbWkl3eg" value="F_CLIENT_20231001.txt"/>
      <node defType="com.stambia.file.record" id="_puTboXpREe6QncsbWkl3eg" name="ENTETE">
        <node defType="com.stambia.file.filter" id="_3GtnMnpREe6QncsbWkl3eg" name="entete">
          <attribute defType="com.stambia.file.filter.value" id="_8mMHoHpREe6QncsbWkl3eg" value="000"/>
          <attribute defType="com.stambia.file.filter.start" id="_80oMQHpREe6QncsbWkl3eg" value="1"/>
          <attribute defType="com.stambia.file.filter.length" id="_9OKtoHpREe6QncsbWkl3eg" value="3"/>
          <attribute defType="com.stambia.file.filter.operator" id="_9vG3gHpREe6QncsbWkl3eg" value="Equals"/>
        </node>
        <node defType="com.stambia.file.field" id="_CuMAo3pSEe6QncsbWkl3eg" name="F3" position="3">
          <attribute defType="com.stambia.file.field.size" id="_CuMApHpSEe6QncsbWkl3eg" value="2"/>
          <attribute defType="com.stambia.file.field.type" id="_CuMApXpSEe6QncsbWkl3eg" value="Numeric"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_CuMApnpSEe6QncsbWkl3eg" value="F3"/>
        </node>
        <node defType="com.stambia.file.field" id="_CuMArHpSEe6QncsbWkl3eg" name="F5" position="5">
          <attribute defType="com.stambia.file.field.size" id="_CuMArXpSEe6QncsbWkl3eg" value="30"/>
          <attribute defType="com.stambia.file.field.type" id="_CuMArnpSEe6QncsbWkl3eg" value="String"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_CuMAr3pSEe6QncsbWkl3eg" value="F5"/>
        </node>
        <node defType="com.stambia.file.field" id="_CuMAp3pSEe6QncsbWkl3eg" name="F4" position="4">
          <attribute defType="com.stambia.file.field.size" id="_CuMAqHpSEe6QncsbWkl3eg" value="30"/>
          <attribute defType="com.stambia.file.field.type" id="_CuMAqXpSEe6QncsbWkl3eg" value="Date"/>
          <attribute defType="com.stambia.file.field.format" id="_CuMAqnpSEe6QncsbWkl3eg" value="yyyy-MM-dd"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_CuMAq3pSEe6QncsbWkl3eg" value="F4"/>
        </node>
        <node defType="com.stambia.file.field" id="_CuLZkHpSEe6QncsbWkl3eg" name="F1" position="1">
          <attribute defType="com.stambia.file.field.size" id="_CuLZkXpSEe6QncsbWkl3eg" value="3"/>
          <attribute defType="com.stambia.file.field.type" id="_CuLZknpSEe6QncsbWkl3eg" value="Numeric"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_CuLZk3pSEe6QncsbWkl3eg" value="F1"/>
        </node>
        <node defType="com.stambia.file.field" id="_CuLZlHpSEe6QncsbWkl3eg" name="F2" position="2">
          <attribute defType="com.stambia.file.field.size" id="_CuMAoHpSEe6QncsbWkl3eg" value="20"/>
          <attribute defType="com.stambia.file.field.type" id="_CuMAoXpSEe6QncsbWkl3eg" value="String"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_CuMAonpSEe6QncsbWkl3eg" value="F2"/>
        </node>
        <node defType="com.stambia.file.field" id="_CuMAsHpSEe6QncsbWkl3eg" name="F6" position="6">
          <attribute defType="com.stambia.file.field.size" id="_CuMAsXpSEe6QncsbWkl3eg" value="6"/>
          <attribute defType="com.stambia.file.field.type" id="_CuMAsnpSEe6QncsbWkl3eg" value="Numeric"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_CuMAs3pSEe6QncsbWkl3eg" value="F6"/>
        </node>
      </node>
      <node defType="com.stambia.file.field" id="_cItvsHpREe6QncsbWkl3eg" name="F1" position="1">
        <attribute defType="com.stambia.file.field.size" id="_cItvsXpREe6QncsbWkl3eg" value="12"/>
        <attribute defType="com.stambia.file.field.type" id="_cItvsnpREe6QncsbWkl3eg" value="Numeric"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_cItvs3pREe6QncsbWkl3eg" value="F1"/>
      </node>
      <node defType="com.stambia.file.field" id="_cItvtHpREe6QncsbWkl3eg" name="F2" position="2">
        <attribute defType="com.stambia.file.field.size" id="_cItvtXpREe6QncsbWkl3eg" value="56"/>
        <attribute defType="com.stambia.file.field.type" id="_cItvtnpREe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_cItvt3pREe6QncsbWkl3eg" value="F2"/>
      </node>
      <node defType="com.stambia.file.field" id="_cItvuHpREe6QncsbWkl3eg" name="F3" position="3">
        <attribute defType="com.stambia.file.field.size" id="_cItvuXpREe6QncsbWkl3eg" value="59"/>
        <attribute defType="com.stambia.file.field.type" id="_cItvunpREe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_cItvu3pREe6QncsbWkl3eg" value="F3"/>
      </node>
      <node defType="com.stambia.file.field" id="_cItvvHpREe6QncsbWkl3eg" name="F4" position="4">
        <attribute defType="com.stambia.file.field.size" id="_cItvvXpREe6QncsbWkl3eg" value="71"/>
        <attribute defType="com.stambia.file.field.type" id="_cItvvnpREe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.format" id="_cItvv3pREe6QncsbWkl3eg" value="yyyy-MM-dd"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_cItvwHpREe6QncsbWkl3eg" value="F4"/>
      </node>
      <node defType="com.stambia.file.field" id="_cItvwXpREe6QncsbWkl3eg" name="F5" position="5">
        <attribute defType="com.stambia.file.field.size" id="_cItvwnpREe6QncsbWkl3eg" value="54"/>
        <attribute defType="com.stambia.file.field.type" id="_cItvw3pREe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_cItvxHpREe6QncsbWkl3eg" value="F5"/>
      </node>
      <node defType="com.stambia.file.field" id="_cItvxXpREe6QncsbWkl3eg" name="F6" position="6">
        <attribute defType="com.stambia.file.field.size" id="_cItvxnpREe6QncsbWkl3eg" value="64"/>
        <attribute defType="com.stambia.file.field.type" id="_cItvx3pREe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_cItvyHpREe6QncsbWkl3eg" value="F6"/>
      </node>
      <node defType="com.stambia.file.record" id="_PE4QgHpSEe6QncsbWkl3eg" name="ENTETE_2">
        <node defType="com.stambia.file.filter" id="_PE4QgXpSEe6QncsbWkl3eg" name="entete">
          <attribute defType="com.stambia.file.filter.value" id="_PE4QgnpSEe6QncsbWkl3eg" value="100"/>
          <attribute defType="com.stambia.file.filter.start" id="_PE4Qg3pSEe6QncsbWkl3eg" value="1"/>
          <attribute defType="com.stambia.file.filter.length" id="_PE4QhHpSEe6QncsbWkl3eg" value="3"/>
          <attribute defType="com.stambia.file.filter.operator" id="_PE4QhXpSEe6QncsbWkl3eg" value="Equals"/>
        </node>
        <node defType="com.stambia.file.field" id="_Wqy5AHpSEe6QncsbWkl3eg" name="F1" position="1">
          <attribute defType="com.stambia.file.field.size" id="_Wqy5AXpSEe6QncsbWkl3eg" value="12"/>
          <attribute defType="com.stambia.file.field.type" id="_Wqy5AnpSEe6QncsbWkl3eg" value="Numeric"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_Wqy5A3pSEe6QncsbWkl3eg" value="F1"/>
        </node>
        <node defType="com.stambia.file.field" id="_Wqy5CHpSEe6QncsbWkl3eg" name="F3" position="3">
          <attribute defType="com.stambia.file.field.size" id="_Wqy5CXpSEe6QncsbWkl3eg" value="59"/>
          <attribute defType="com.stambia.file.field.type" id="_Wqy5CnpSEe6QncsbWkl3eg" value="String"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_Wqy5C3pSEe6QncsbWkl3eg" value="F3"/>
        </node>
        <node defType="com.stambia.file.field" id="_Wqy5DHpSEe6QncsbWkl3eg" name="F4" position="4">
          <attribute defType="com.stambia.file.field.size" id="_Wqy5DXpSEe6QncsbWkl3eg" value="12"/>
          <attribute defType="com.stambia.file.field.type" id="_Wqy5DnpSEe6QncsbWkl3eg" value="Numeric"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_Wqy5D3pSEe6QncsbWkl3eg" value="F4"/>
        </node>
        <node defType="com.stambia.file.field" id="_Wqy5FHpSEe6QncsbWkl3eg" name="F6" position="6">
          <attribute defType="com.stambia.file.field.size" id="_Wqy5FXpSEe6QncsbWkl3eg" value="12"/>
          <attribute defType="com.stambia.file.field.type" id="_Wqy5FnpSEe6QncsbWkl3eg" value="Numeric"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_Wqy5F3pSEe6QncsbWkl3eg" value="F6"/>
        </node>
        <node defType="com.stambia.file.field" id="_Wqy5BHpSEe6QncsbWkl3eg" name="F2" position="2">
          <attribute defType="com.stambia.file.field.size" id="_Wqy5BXpSEe6QncsbWkl3eg" value="51"/>
          <attribute defType="com.stambia.file.field.type" id="_Wqy5BnpSEe6QncsbWkl3eg" value="String"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_Wqy5B3pSEe6QncsbWkl3eg" value="F2"/>
        </node>
        <node defType="com.stambia.file.field" id="_Wqy5EHpSEe6QncsbWkl3eg" name="F5" position="5">
          <attribute defType="com.stambia.file.field.size" id="_Wqy5EXpSEe6QncsbWkl3eg" value="12"/>
          <attribute defType="com.stambia.file.field.type" id="_Wqy5EnpSEe6QncsbWkl3eg" value="Numeric"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_Wqy5E3pSEe6QncsbWkl3eg" value="F5"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.file.file" id="_lN_SIHpREe6QncsbWkl3eg" name="F_CLIENT_20231001_2">
      <attribute defType="com.stambia.file.file.type" id="_lN_SIXpREe6QncsbWkl3eg" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.charsetName" id="_lN_SInpREe6QncsbWkl3eg"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_lN_SI3pREe6QncsbWkl3eg" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_lN_SJHpREe6QncsbWkl3eg" value="7C"/>
      <attribute defType="com.stambia.file.file.stringDelimiter" id="_lN_SJXpREe6QncsbWkl3eg"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_lN_SJnpREe6QncsbWkl3eg" value="2E"/>
      <attribute defType="com.stambia.file.file.escapeChar" id="_lN_SJ3pREe6QncsbWkl3eg"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_lN_SKHpREe6QncsbWkl3eg" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_lN_SKXpREe6QncsbWkl3eg" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_lN_SKnpREe6QncsbWkl3eg" value="0"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_lN_SK3pREe6QncsbWkl3eg" value="F_CLIENT_20231001.txt"/>
      <node defType="com.stambia.file.field" id="_lN_SLHpREe6QncsbWkl3eg" name="F4" position="4">
        <attribute defType="com.stambia.file.field.size" id="_lN_SLXpREe6QncsbWkl3eg" value="71"/>
        <attribute defType="com.stambia.file.field.type" id="_lN_SLnpREe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.format" id="_lN_SL3pREe6QncsbWkl3eg" value="yyyy-MM-dd"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_lN_SMHpREe6QncsbWkl3eg" value="F4"/>
      </node>
      <node defType="com.stambia.file.field" id="_lN_SMXpREe6QncsbWkl3eg" name="F6" position="6">
        <attribute defType="com.stambia.file.field.size" id="_lN_SMnpREe6QncsbWkl3eg" value="64"/>
        <attribute defType="com.stambia.file.field.type" id="_lN_SM3pREe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_lN_5MHpREe6QncsbWkl3eg" value="F6"/>
      </node>
      <node defType="com.stambia.file.field" id="_lN_5MXpREe6QncsbWkl3eg" name="F3" position="3">
        <attribute defType="com.stambia.file.field.size" id="_lN_5MnpREe6QncsbWkl3eg" value="59"/>
        <attribute defType="com.stambia.file.field.type" id="_lN_5M3pREe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_lN_5NHpREe6QncsbWkl3eg" value="F3"/>
      </node>
      <node defType="com.stambia.file.field" id="_lN_5NXpREe6QncsbWkl3eg" name="F2" position="2">
        <attribute defType="com.stambia.file.field.size" id="_lN_5NnpREe6QncsbWkl3eg" value="56"/>
        <attribute defType="com.stambia.file.field.type" id="_lN_5N3pREe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_lN_5OHpREe6QncsbWkl3eg" value="F2"/>
      </node>
      <node defType="com.stambia.file.field" id="_lN_5OXpREe6QncsbWkl3eg" name="F1" position="1">
        <attribute defType="com.stambia.file.field.size" id="_lN_5OnpREe6QncsbWkl3eg" value="12"/>
        <attribute defType="com.stambia.file.field.type" id="_lN_5O3pREe6QncsbWkl3eg" value="Numeric"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_lN_5PHpREe6QncsbWkl3eg" value="F1"/>
      </node>
      <node defType="com.stambia.file.field" id="_lN_5PXpREe6QncsbWkl3eg" name="F5" position="5">
        <attribute defType="com.stambia.file.field.size" id="_lN_5PnpREe6QncsbWkl3eg" value="54"/>
        <attribute defType="com.stambia.file.field.type" id="_lN_5P3pREe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_lN_5QHpREe6QncsbWkl3eg" value="F5"/>
      </node>
    </node>
  </node>
</md:node>