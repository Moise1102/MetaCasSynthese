<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.file.server" id="_FaryAHokEe6cgaTnMFlv7A" name="source" md:ref="resource.md#UUID_TECH_FILE_MD?fileId=UUID_TECH_FILE_MD$type=md$name=File?" internalVersion="v1.0.0">
  <node defType="com.stambia.file.directory" id="_WWqRgHpREe6QncsbWkl3eg" name="source">
    <attribute defType="com.stambia.file.directory.path" id="_WXn60HpREe6QncsbWkl3eg" value="C:\source"/>
    <node defType="com.stambia.file.file" id="_WXq-IHpREe6QncsbWkl3eg" name="F_CLIENT_20231001">
      <attribute defType="com.stambia.file.file.type" id="_WYYv0HpREe6QncsbWkl3eg" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.charsetName" id="_WYZ98HpREe6QncsbWkl3eg" value="UTF-8"/>
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
        <node defType="com.stambia.file.field" id="_CuMAo3pSEe6QncsbWkl3eg" name="VERSION" position="3">
          <attribute defType="com.stambia.file.field.size" id="_CuMApHpSEe6QncsbWkl3eg" value="2"/>
          <attribute defType="com.stambia.file.field.type" id="_CuMApXpSEe6QncsbWkl3eg" value="Numeric"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_CuMApnpSEe6QncsbWkl3eg" value="F3"/>
        </node>
        <node defType="com.stambia.file.field" id="_CuMArHpSEe6QncsbWkl3eg" name="SOURCE" position="5">
          <attribute defType="com.stambia.file.field.size" id="_CuMArXpSEe6QncsbWkl3eg" value="30"/>
          <attribute defType="com.stambia.file.field.type" id="_CuMArnpSEe6QncsbWkl3eg" value="String"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_CuMAr3pSEe6QncsbWkl3eg" value="F5"/>
        </node>
        <node defType="com.stambia.file.field" id="_CuMAp3pSEe6QncsbWkl3eg" name="DATE" position="4">
          <attribute defType="com.stambia.file.field.size" id="_CuMAqHpSEe6QncsbWkl3eg" value="30"/>
          <attribute defType="com.stambia.file.field.type" id="_CuMAqXpSEe6QncsbWkl3eg" value="Date"/>
          <attribute defType="com.stambia.file.field.format" id="_CuMAqnpSEe6QncsbWkl3eg" value="yyyy-MM-dd"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_CuMAq3pSEe6QncsbWkl3eg" value="F4"/>
        </node>
        <node defType="com.stambia.file.field" id="_CuLZkHpSEe6QncsbWkl3eg" name="TYPE_LIGNE" position="1">
          <attribute defType="com.stambia.file.field.size" id="_CuLZkXpSEe6QncsbWkl3eg" value="3"/>
          <attribute defType="com.stambia.file.field.type" id="_CuLZknpSEe6QncsbWkl3eg" value="String"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_CuLZk3pSEe6QncsbWkl3eg" value="F1"/>
        </node>
        <node defType="com.stambia.file.field" id="_CuLZlHpSEe6QncsbWkl3eg" name="TYPE_FICHIER" position="2">
          <attribute defType="com.stambia.file.field.size" id="_CuMAoHpSEe6QncsbWkl3eg" value="20"/>
          <attribute defType="com.stambia.file.field.type" id="_CuMAoXpSEe6QncsbWkl3eg" value="String"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_CuMAonpSEe6QncsbWkl3eg" value="F2"/>
        </node>
        <node defType="com.stambia.file.field" id="_CuMAsHpSEe6QncsbWkl3eg" name="SEQUENCE" position="6">
          <attribute defType="com.stambia.file.field.size" id="_CuMAsXpSEe6QncsbWkl3eg" value="6"/>
          <attribute defType="com.stambia.file.field.type" id="_CuMAsnpSEe6QncsbWkl3eg" value="Numeric"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_CuMAs3pSEe6QncsbWkl3eg" value="F6"/>
        </node>
      </node>
      <node defType="com.stambia.file.record" id="_PE4QgHpSEe6QncsbWkl3eg" name="COMPTE">
        <node defType="com.stambia.file.filter" id="_PE4QgXpSEe6QncsbWkl3eg" name="COMPTE">
          <attribute defType="com.stambia.file.filter.value" id="_PE4QgnpSEe6QncsbWkl3eg" value="100"/>
          <attribute defType="com.stambia.file.filter.start" id="_PE4Qg3pSEe6QncsbWkl3eg" value="1"/>
          <attribute defType="com.stambia.file.filter.length" id="_PE4QhHpSEe6QncsbWkl3eg" value="3"/>
          <attribute defType="com.stambia.file.filter.operator" id="_PE4QhXpSEe6QncsbWkl3eg" value="Equals"/>
        </node>
        <node defType="com.stambia.file.field" id="_Wqy5AHpSEe6QncsbWkl3eg" name="TYPE_LIGNE" position="1">
          <attribute defType="com.stambia.file.field.size" id="_Wqy5AXpSEe6QncsbWkl3eg" value="3"/>
          <attribute defType="com.stambia.file.field.type" id="_Wqy5AnpSEe6QncsbWkl3eg" value="Numeric"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_Wqy5A3pSEe6QncsbWkl3eg" value="TYPE_LIGNE"/>
        </node>
        <node defType="com.stambia.file.field" id="_Wqy5CHpSEe6QncsbWkl3eg" name="CLE_COMPTE" position="3">
          <attribute defType="com.stambia.file.field.size" id="_Wqy5CXpSEe6QncsbWkl3eg" value="45"/>
          <attribute defType="com.stambia.file.field.type" id="_Wqy5CnpSEe6QncsbWkl3eg" value="String"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_Wqy5C3pSEe6QncsbWkl3eg" value="CLE_COMPTE"/>
        </node>
        <node defType="com.stambia.file.field" id="_Wqy5DHpSEe6QncsbWkl3eg" name="STATUS" position="4">
          <attribute defType="com.stambia.file.field.size" id="_Wqy5DXpSEe6QncsbWkl3eg" value="5"/>
          <attribute defType="com.stambia.file.field.type" id="_Wqy5DnpSEe6QncsbWkl3eg" value="Numeric"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_Wqy5D3pSEe6QncsbWkl3eg" value="STATUS"/>
        </node>
        <node defType="com.stambia.file.field" id="_Wqy5FHpSEe6QncsbWkl3eg" name="CABINET" position="6">
          <attribute defType="com.stambia.file.field.size" id="_Wqy5FXpSEe6QncsbWkl3eg" value="9"/>
          <attribute defType="com.stambia.file.field.type" id="_Wqy5FnpSEe6QncsbWkl3eg" value="Numeric"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_Wqy5F3pSEe6QncsbWkl3eg" value="CABINET"/>
        </node>
        <node defType="com.stambia.file.field" id="_Wqy5BHpSEe6QncsbWkl3eg" name="ACTION" position="2">
          <attribute defType="com.stambia.file.field.size" id="_Wqy5BXpSEe6QncsbWkl3eg" value="1"/>
          <attribute defType="com.stambia.file.field.type" id="_Wqy5BnpSEe6QncsbWkl3eg" value="String"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_Wqy5B3pSEe6QncsbWkl3eg" value="ACTION"/>
        </node>
        <node defType="com.stambia.file.field" id="_Wqy5EHpSEe6QncsbWkl3eg" name="TYPE" position="5">
          <attribute defType="com.stambia.file.field.size" id="_Wqy5EXpSEe6QncsbWkl3eg" value="5"/>
          <attribute defType="com.stambia.file.field.type" id="_Wqy5EnpSEe6QncsbWkl3eg" value="Numeric"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_Wqy5E3pSEe6QncsbWkl3eg" value="TYPE"/>
        </node>
        <node defType="com.stambia.file.record" id="_uvITkXqFEe6F_fnQESD-eA" name="CLIENT">
          <node defType="com.stambia.file.filter" id="_xZ_-YnqFEe6F_fnQESD-eA" name="client">
            <attribute defType="com.stambia.file.filter.value" id="_2uxDoHqFEe6F_fnQESD-eA" value="200"/>
            <attribute defType="com.stambia.file.filter.start" id="_3GKP8HqFEe6F_fnQESD-eA" value="1"/>
            <attribute defType="com.stambia.file.filter.length" id="_3hVJAHqFEe6F_fnQESD-eA" value="3"/>
            <attribute defType="com.stambia.file.filter.operator" id="_4BEZAHqFEe6F_fnQESD-eA" value="Equals"/>
          </node>
          <node defType="com.stambia.file.field" id="_5aYVcHqFEe6F_fnQESD-eA" name="DATE_ANNIVERSAIRE" position="10">
            <attribute defType="com.stambia.file.field.size" id="_5aYVcXqFEe6F_fnQESD-eA" value="10"/>
            <attribute defType="com.stambia.file.field.type" id="_5aYVcnqFEe6F_fnQESD-eA" value="Numeric"/>
            <attribute defType="com.stambia.file.field.physicalName" id="_5aYVc3qFEe6F_fnQESD-eA" value="F10"/>
          </node>
          <node defType="com.stambia.file.field" id="_5aYVbHqFEe6F_fnQESD-eA" name="NOM" position="9">
            <attribute defType="com.stambia.file.field.size" id="_5aYVbXqFEe6F_fnQESD-eA" value="255"/>
            <attribute defType="com.stambia.file.field.type" id="_5aYVbnqFEe6F_fnQESD-eA" value="String"/>
            <attribute defType="com.stambia.file.field.physicalName" id="_5aYVb3qFEe6F_fnQESD-eA" value="F9"/>
          </node>
          <node defType="com.stambia.file.field" id="_5aYVVHqFEe6F_fnQESD-eA" name="CLE_CLIENT" position="3">
            <attribute defType="com.stambia.file.field.size" id="_5aYVVXqFEe6F_fnQESD-eA" value="45"/>
            <attribute defType="com.stambia.file.field.type" id="_5aYVVnqFEe6F_fnQESD-eA" value="String"/>
            <attribute defType="com.stambia.file.field.physicalName" id="_5aYVV3qFEe6F_fnQESD-eA" value="F3"/>
          </node>
          <node defType="com.stambia.file.field" id="_5aTc0HqFEe6F_fnQESD-eA" name="TYPE_LIGNE" position="1">
            <attribute defType="com.stambia.file.field.size" id="_5aTc0XqFEe6F_fnQESD-eA" value="3"/>
            <attribute defType="com.stambia.file.field.type" id="_5aTc0nqFEe6F_fnQESD-eA" value="String"/>
            <attribute defType="com.stambia.file.field.physicalName" id="_5aTc03qFEe6F_fnQESD-eA" value="F1"/>
          </node>
          <node defType="com.stambia.file.field" id="_5aYVeHqFEe6F_fnQESD-eA" name="MUTUELLE" position="12">
            <attribute defType="com.stambia.file.field.size" id="_5aYVeXqFEe6F_fnQESD-eA" value="5"/>
            <attribute defType="com.stambia.file.field.type" id="_5aYVenqFEe6F_fnQESD-eA" value="Numeric"/>
            <attribute defType="com.stambia.file.field.physicalName" id="_5aYVe3qFEe6F_fnQESD-eA" value="F12"/>
          </node>
          <node defType="com.stambia.file.field" id="_5aYVWHqFEe6F_fnQESD-eA" name="CLE_COMPTE" position="4">
            <attribute defType="com.stambia.file.field.size" id="_5aYVWXqFEe6F_fnQESD-eA" value="45"/>
            <attribute defType="com.stambia.file.field.type" id="_5aYVWnqFEe6F_fnQESD-eA" value="String"/>
            <attribute defType="com.stambia.file.field.physicalName" id="_5aYVW3qFEe6F_fnQESD-eA" value="F4"/>
          </node>
          <node defType="com.stambia.file.field" id="_5aYVZHqFEe6F_fnQESD-eA" name="CIVILITE" position="7">
            <attribute defType="com.stambia.file.field.size" id="_5aYVZXqFEe6F_fnQESD-eA" value="5"/>
            <attribute defType="com.stambia.file.field.type" id="_5aYVZnqFEe6F_fnQESD-eA" value="Numeric"/>
            <attribute defType="com.stambia.file.field.physicalName" id="_5aYVZ3qFEe6F_fnQESD-eA" value="F7"/>
          </node>
          <node defType="com.stambia.file.field" id="_5aYVUHqFEe6F_fnQESD-eA" name="ACTION" position="2">
            <attribute defType="com.stambia.file.field.size" id="_5aYVUXqFEe6F_fnQESD-eA" value="1"/>
            <attribute defType="com.stambia.file.field.type" id="_5aYVUnqFEe6F_fnQESD-eA" value="String"/>
            <attribute defType="com.stambia.file.field.physicalName" id="_5aYVU3qFEe6F_fnQESD-eA" value="F2"/>
          </node>
          <node defType="com.stambia.file.field" id="_5aYVYHqFEe6F_fnQESD-eA" name="TYPE" position="6">
            <attribute defType="com.stambia.file.field.size" id="_5aYVYXqFEe6F_fnQESD-eA" value="5"/>
            <attribute defType="com.stambia.file.field.type" id="_5aYVYnqFEe6F_fnQESD-eA" value="Numeric"/>
            <attribute defType="com.stambia.file.field.physicalName" id="_5aYVY3qFEe6F_fnQESD-eA" value="F6"/>
          </node>
          <node defType="com.stambia.file.field" id="_5aYVXHqFEe6F_fnQESD-eA" name="STATUS" position="5">
            <attribute defType="com.stambia.file.field.size" id="_5aYVXXqFEe6F_fnQESD-eA" value="5"/>
            <attribute defType="com.stambia.file.field.type" id="_5aYVXnqFEe6F_fnQESD-eA" value="Numeric"/>
            <attribute defType="com.stambia.file.field.physicalName" id="_5aYVX3qFEe6F_fnQESD-eA" value="F5"/>
          </node>
          <node defType="com.stambia.file.field" id="_5aYVaHqFEe6F_fnQESD-eA" name="PRENOM" position="8">
            <attribute defType="com.stambia.file.field.size" id="_5aYVaXqFEe6F_fnQESD-eA" value="255"/>
            <attribute defType="com.stambia.file.field.type" id="_5aYVanqFEe6F_fnQESD-eA" value="String"/>
            <attribute defType="com.stambia.file.field.physicalName" id="_5aYVa3qFEe6F_fnQESD-eA" value="F8"/>
          </node>
          <node defType="com.stambia.file.field" id="_5aYVdHqFEe6F_fnQESD-eA" name="SEXE" position="11">
            <attribute defType="com.stambia.file.field.size" id="_5aYVdXqFEe6F_fnQESD-eA" value="5"/>
            <attribute defType="com.stambia.file.field.type" id="_5aYVdnqFEe6F_fnQESD-eA" value="Numeric"/>
            <attribute defType="com.stambia.file.field.physicalName" id="_5aYVd3qFEe6F_fnQESD-eA" value="F11"/>
          </node>
          <node defType="com.stambia.file.record" id="_gWvbsXyIEe6F_fnQESD-eA" name="EMAIL_CLIENT">
            <node defType="com.stambia.file.filter" id="_of8XcnyIEe6F_fnQESD-eA" name="email">
              <attribute defType="com.stambia.file.filter.value" id="_ruc60HyIEe6F_fnQESD-eA" value="203"/>
              <attribute defType="com.stambia.file.filter.start" id="_r7LvQHyIEe6F_fnQESD-eA" value="1"/>
              <attribute defType="com.stambia.file.filter.length" id="_sYOQkHyIEe6F_fnQESD-eA" value="3"/>
              <attribute defType="com.stambia.file.filter.operator" id="_s19VcHyIEe6F_fnQESD-eA" value="Equals"/>
            </node>
            <node defType="com.stambia.file.field" id="_1p0XxHyIEe6F_fnQESD-eA" name="CLE_CLIENT" position="3">
              <attribute defType="com.stambia.file.field.size" id="_1p0XxXyIEe6F_fnQESD-eA" value="45"/>
              <attribute defType="com.stambia.file.field.type" id="_1p0XxnyIEe6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_1p0Xx3yIEe6F_fnQESD-eA" value="CLE_CLIENT"/>
            </node>
            <node defType="com.stambia.file.field" id="_1p0XzHyIEe6F_fnQESD-eA" name="STATUS" position="5">
              <attribute defType="com.stambia.file.field.size" id="_1p0XzXyIEe6F_fnQESD-eA" value="5"/>
              <attribute defType="com.stambia.file.field.type" id="_1p0XznyIEe6F_fnQESD-eA" value="Numeric"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_1p0Xz3yIEe6F_fnQESD-eA" value="STATUS"/>
            </node>
            <node defType="com.stambia.file.field" id="_1pzwsHyIEe6F_fnQESD-eA" name="TYPE_LIGNE" position="1">
              <attribute defType="com.stambia.file.field.size" id="_1pzwsXyIEe6F_fnQESD-eA" value="3"/>
              <attribute defType="com.stambia.file.field.type" id="_1pzwsnyIEe6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_1pzws3yIEe6F_fnQESD-eA" value="TYPE_LIGNE"/>
            </node>
            <node defType="com.stambia.file.field" id="_1p0XwHyIEe6F_fnQESD-eA" name="ACTION" position="2">
              <attribute defType="com.stambia.file.field.size" id="_1p0XwXyIEe6F_fnQESD-eA" value="1"/>
              <attribute defType="com.stambia.file.field.type" id="_1p0XwnyIEe6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_1p0Xw3yIEe6F_fnQESD-eA" value="ACTION"/>
            </node>
            <node defType="com.stambia.file.field" id="_1p0XyHyIEe6F_fnQESD-eA" name="EMAIL" position="4">
              <attribute defType="com.stambia.file.field.size" id="_1p0XyXyIEe6F_fnQESD-eA" value="255"/>
              <attribute defType="com.stambia.file.field.type" id="_1p0XynyIEe6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_1p0Xy3yIEe6F_fnQESD-eA" value="EMAIL"/>
            </node>
            <node defType="com.stambia.file.propertyField" id="_moCDtHzBEe6F_fnQESD-eA" name="fichier_parent">
              <attribute defType="com.stambia.file.propertyField.property" id="_np3UIHzBEe6F_fnQESD-eA" value="file_name"/>
            </node>
          </node>
          <node defType="com.stambia.file.record" id="_IRa2IXy3Ee6F_fnQESD-eA" name="ADRESSE">
            <node defType="com.stambia.file.filter" id="_Lw_7Yny3Ee6F_fnQESD-eA" name="adresse">
              <attribute defType="com.stambia.file.filter.value" id="_ZN3wMHy3Ee6F_fnQESD-eA" value="204"/>
              <attribute defType="com.stambia.file.filter.start" id="_Ze0WQHy3Ee6F_fnQESD-eA" value="1"/>
              <attribute defType="com.stambia.file.filter.length" id="_Z4NGoHy3Ee6F_fnQESD-eA" value="3"/>
              <attribute defType="com.stambia.file.filter.operator" id="_aLG0gHy3Ee6F_fnQESD-eA" value="Equals"/>
            </node>
            <node defType="com.stambia.file.field" id="_hlSHNHy3Ee6F_fnQESD-eA" name="VILLE" position="10">
              <attribute defType="com.stambia.file.field.size" id="_hlSHNXy3Ee6F_fnQESD-eA" value="50"/>
              <attribute defType="com.stambia.file.field.type" id="_hlSHNny3Ee6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_hlSHN3y3Ee6F_fnQESD-eA" value="F10"/>
            </node>
            <node defType="com.stambia.file.field" id="_hlSHFHy3Ee6F_fnQESD-eA" name="ACTION" position="2">
              <attribute defType="com.stambia.file.field.size" id="_hlSHFXy3Ee6F_fnQESD-eA" value="1"/>
              <attribute defType="com.stambia.file.field.type" id="_hlSHFny3Ee6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_hlSHF3y3Ee6F_fnQESD-eA" value="F2"/>
            </node>
            <node defType="com.stambia.file.field" id="_hlSHJHy3Ee6F_fnQESD-eA" name="LIGNE_2" position="6">
              <attribute defType="com.stambia.file.field.size" id="_hlSHJXy3Ee6F_fnQESD-eA" value="255"/>
              <attribute defType="com.stambia.file.field.type" id="_hlSHJny3Ee6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_hlSHJ3y3Ee6F_fnQESD-eA" value="F6"/>
            </node>
            <node defType="com.stambia.file.field" id="_hlSHHHy3Ee6F_fnQESD-eA" name="STATUS" position="4">
              <attribute defType="com.stambia.file.field.size" id="_hlSHHXy3Ee6F_fnQESD-eA" value="5"/>
              <attribute defType="com.stambia.file.field.type" id="_hlSHHny3Ee6F_fnQESD-eA" value="Numeric"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_hlSHH3y3Ee6F_fnQESD-eA" value="F4"/>
            </node>
            <node defType="com.stambia.file.field" id="_hlSHIHy3Ee6F_fnQESD-eA" name="LIGNE_1" position="5">
              <attribute defType="com.stambia.file.field.size" id="_hlSHIXy3Ee6F_fnQESD-eA" value="255"/>
              <attribute defType="com.stambia.file.field.type" id="_hlSHIny3Ee6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_hlSHI3y3Ee6F_fnQESD-eA" value="F5"/>
            </node>
            <node defType="com.stambia.file.field" id="_hlSHLHy3Ee6F_fnQESD-eA" name="LIGNE_4" position="8">
              <attribute defType="com.stambia.file.field.size" id="_hlSHLXy3Ee6F_fnQESD-eA" value="255"/>
              <attribute defType="com.stambia.file.field.type" id="_hlSHLny3Ee6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_hlSHL3y3Ee6F_fnQESD-eA" value="F8"/>
            </node>
            <node defType="com.stambia.file.field" id="_hlSHGHy3Ee6F_fnQESD-eA" name="CLIENT" position="3">
              <attribute defType="com.stambia.file.field.size" id="_hlSHGXy3Ee6F_fnQESD-eA" value="45"/>
              <attribute defType="com.stambia.file.field.type" id="_hlSHGny3Ee6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_hlSHG3y3Ee6F_fnQESD-eA" value="F3"/>
            </node>
            <node defType="com.stambia.file.field" id="_hlSHMHy3Ee6F_fnQESD-eA" name="LIGNE_5" position="9">
              <attribute defType="com.stambia.file.field.size" id="_hlSHMXy3Ee6F_fnQESD-eA" value="255"/>
              <attribute defType="com.stambia.file.field.type" id="_hlSHMny3Ee6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_hlSHM3y3Ee6F_fnQESD-eA" value="F9"/>
            </node>
            <node defType="com.stambia.file.field" id="_hlSHQHy3Ee6F_fnQESD-eA" name="QUALITE" position="13">
              <attribute defType="com.stambia.file.field.size" id="_hlSHQXy3Ee6F_fnQESD-eA" value="1"/>
              <attribute defType="com.stambia.file.field.type" id="_hlSHQny3Ee6F_fnQESD-eA" value="Numeric"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_hlSHQ3y3Ee6F_fnQESD-eA" value="F13"/>
            </node>
            <node defType="com.stambia.file.field" id="_hlSHKHy3Ee6F_fnQESD-eA" name="LIGNE_3" position="7">
              <attribute defType="com.stambia.file.field.size" id="_hlSHKXy3Ee6F_fnQESD-eA" value="255"/>
              <attribute defType="com.stambia.file.field.type" id="_hlSHKny3Ee6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_hlSHK3y3Ee6F_fnQESD-eA" value="F7"/>
            </node>
            <node defType="com.stambia.file.field" id="_hlSHOHy3Ee6F_fnQESD-eA" name="CODE_POSTAL" position="11">
              <attribute defType="com.stambia.file.field.size" id="_hlSHOXy3Ee6F_fnQESD-eA" value="10"/>
              <attribute defType="com.stambia.file.field.type" id="_hlSHOny3Ee6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_hlSHO3y3Ee6F_fnQESD-eA" value="F11"/>
            </node>
            <node defType="com.stambia.file.field" id="_hlSHPHy3Ee6F_fnQESD-eA" name="PAYS" position="12">
              <attribute defType="com.stambia.file.field.size" id="_hlSHPXy3Ee6F_fnQESD-eA" value="5"/>
              <attribute defType="com.stambia.file.field.type" id="_hlSHPny3Ee6F_fnQESD-eA" value="Numeric"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_hlSHP3y3Ee6F_fnQESD-eA" value="F12"/>
            </node>
            <node defType="com.stambia.file.field" id="_hlSHEHy3Ee6F_fnQESD-eA" name="TYPE_LIGNE" position="1">
              <attribute defType="com.stambia.file.field.size" id="_hlSHEXy3Ee6F_fnQESD-eA" value="3"/>
              <attribute defType="com.stambia.file.field.type" id="_hlSHEny3Ee6F_fnQESD-eA" value="Numeric"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_hlSHE3y3Ee6F_fnQESD-eA" value="F1"/>
            </node>
          </node>
          <node defType="com.stambia.file.record" id="_NhTUAXy6Ee6F_fnQESD-eA" name="TELEPHONE">
            <node defType="com.stambia.file.filter" id="_OJqUgny6Ee6F_fnQESD-eA" name="telephone">
              <attribute defType="com.stambia.file.filter.value" id="_9TOGYHy6Ee6F_fnQESD-eA" value="205"/>
              <attribute defType="com.stambia.file.filter.start" id="_9jev8Hy6Ee6F_fnQESD-eA" value="1"/>
              <attribute defType="com.stambia.file.filter.length" id="_-B2uAHy6Ee6F_fnQESD-eA" value="3"/>
              <attribute defType="com.stambia.file.filter.operator" id="_-Yba8Hy6Ee6F_fnQESD-eA" value="Equals"/>
            </node>
            <node defType="com.stambia.file.field" id="_IQ1qlHy7Ee6F_fnQESD-eA" name="FAVORI" position="6">
              <attribute defType="com.stambia.file.field.size" id="_IQ1qlXy7Ee6F_fnQESD-eA" value="5"/>
              <attribute defType="com.stambia.file.field.type" id="_IQ1qlny7Ee6F_fnQESD-eA" value="Numeric"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_IQ1ql3y7Ee6F_fnQESD-eA" value="F6"/>
            </node>
            <node defType="com.stambia.file.field" id="_IQ1qjHy7Ee6F_fnQESD-eA" name="PHONE" position="4">
              <attribute defType="com.stambia.file.field.size" id="_IQ1qjXy7Ee6F_fnQESD-eA" value="45"/>
              <attribute defType="com.stambia.file.field.type" id="_IQ1qjny7Ee6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_IQ1qj3y7Ee6F_fnQESD-eA" value="F4"/>
            </node>
            <node defType="com.stambia.file.field" id="_IQ1qkHy7Ee6F_fnQESD-eA" name="STATUS" position="5">
              <attribute defType="com.stambia.file.field.size" id="_IQ1qkXy7Ee6F_fnQESD-eA" value="5"/>
              <attribute defType="com.stambia.file.field.type" id="_IQ1qkny7Ee6F_fnQESD-eA" value="Numeric"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_IQ1qk3y7Ee6F_fnQESD-eA" value="F5"/>
            </node>
            <node defType="com.stambia.file.field" id="_IQ1qiHy7Ee6F_fnQESD-eA" name="CLE_CLIENT" position="3">
              <attribute defType="com.stambia.file.field.size" id="_IQ1qiXy7Ee6F_fnQESD-eA" value="45"/>
              <attribute defType="com.stambia.file.field.type" id="_IQ1qiny7Ee6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_IQ1qi3y7Ee6F_fnQESD-eA" value="F3"/>
            </node>
            <node defType="com.stambia.file.field" id="_IQ1qmHy7Ee6F_fnQESD-eA" name="TYPE" position="7">
              <attribute defType="com.stambia.file.field.size" id="_IQ1qmXy7Ee6F_fnQESD-eA" value="5"/>
              <attribute defType="com.stambia.file.field.type" id="_IQ1qmny7Ee6F_fnQESD-eA" value="Numeric"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_IQ1qm3y7Ee6F_fnQESD-eA" value="F7"/>
            </node>
            <node defType="com.stambia.file.field" id="_IQ1qgHy7Ee6F_fnQESD-eA" name="TYPE_LIGNE " position="1">
              <attribute defType="com.stambia.file.field.size" id="_IQ1qgXy7Ee6F_fnQESD-eA" value="3"/>
              <attribute defType="com.stambia.file.field.type" id="_IQ1qgny7Ee6F_fnQESD-eA" value="Numeric"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_IQ1qg3y7Ee6F_fnQESD-eA" value="F1"/>
            </node>
            <node defType="com.stambia.file.field" id="_IQ1qhHy7Ee6F_fnQESD-eA" name="ACTION" position="2">
              <attribute defType="com.stambia.file.field.size" id="_IQ1qhXy7Ee6F_fnQESD-eA" value="1"/>
              <attribute defType="com.stambia.file.field.type" id="_IQ1qhny7Ee6F_fnQESD-eA" value="String"/>
              <attribute defType="com.stambia.file.field.physicalName" id="_IQ1qh3y7Ee6F_fnQESD-eA" value="F2"/>
            </node>
          </node>
        </node>
        <node defType="com.stambia.file.propertyField" id="_dxeStHzBEe6F_fnQESD-eA" name="fichier_parent">
          <attribute defType="com.stambia.file.propertyField.property" id="_jURM4HzBEe6F_fnQESD-eA" value="file_parent_name"/>
        </node>
      </node>
      <node defType="com.stambia.file.record" id="_jQxbsXy7Ee6F_fnQESD-eA" name="PIED">
        <node defType="com.stambia.file.filter" id="_lcg6gny7Ee6F_fnQESD-eA" name="pied">
          <attribute defType="com.stambia.file.filter.value" id="_mcg-8Hy7Ee6F_fnQESD-eA" value="999"/>
          <attribute defType="com.stambia.file.filter.start" id="_nIi-gHy7Ee6F_fnQESD-eA" value="1"/>
          <attribute defType="com.stambia.file.filter.length" id="_nm1dAHy7Ee6F_fnQESD-eA" value="3"/>
          <attribute defType="com.stambia.file.filter.operator" id="_oAAK8Hy7Ee6F_fnQESD-eA" value="Equals"/>
        </node>
        <node defType="com.stambia.file.field" id="_qzN5dHy7Ee6F_fnQESD-eA" name="NB_LIGNE" position="2">
          <attribute defType="com.stambia.file.field.size" id="_qzN5dXy7Ee6F_fnQESD-eA" value="10"/>
          <attribute defType="com.stambia.file.field.type" id="_qzN5dny7Ee6F_fnQESD-eA" value="Numeric"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_qzN5d3y7Ee6F_fnQESD-eA" value="F2"/>
        </node>
        <node defType="com.stambia.file.field" id="_qzN5cHy7Ee6F_fnQESD-eA" name="TYPE_LIGNE" position="1">
          <attribute defType="com.stambia.file.field.size" id="_qzN5cXy7Ee6F_fnQESD-eA" value="3"/>
          <attribute defType="com.stambia.file.field.type" id="_qzN5cny7Ee6F_fnQESD-eA" value="String"/>
          <attribute defType="com.stambia.file.field.physicalName" id="_qzN5c3y7Ee6F_fnQESD-eA" value="F1"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.file.file" id="_lN_SIHpREe6QncsbWkl3eg" name="F_CLIENT_20231001_2">
      <attribute defType="com.stambia.file.file.type" id="_lN_SIXpREe6QncsbWkl3eg" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.charsetName" id="_lN_SInpREe6QncsbWkl3eg" value="UTF-8"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_lN_SI3pREe6QncsbWkl3eg" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_lN_SJHpREe6QncsbWkl3eg" value="7C"/>
      <attribute defType="com.stambia.file.file.stringDelimiter" id="_lN_SJXpREe6QncsbWkl3eg"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_lN_SJnpREe6QncsbWkl3eg" value="2E"/>
      <attribute defType="com.stambia.file.file.escapeChar" id="_lN_SJ3pREe6QncsbWkl3eg"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_lN_SKHpREe6QncsbWkl3eg" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_lN_SKXpREe6QncsbWkl3eg" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_lN_SKnpREe6QncsbWkl3eg" value="0"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_lN_SK3pREe6QncsbWkl3eg" value="F_CLIENT_4.txt"/>
      <node defType="com.stambia.file.field" id="_lN_SLHpREe6QncsbWkl3eg" name="F4" position="4">
        <attribute defType="com.stambia.file.field.size" id="_lN_SLXpREe6QncsbWkl3eg" value="71"/>
        <attribute defType="com.stambia.file.field.type" id="_lN_SLnpREe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.format" id="_lN_SL3pREe6QncsbWkl3eg" value="yyyy-MM-dd"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_lN_SMHpREe6QncsbWkl3eg" value="F4"/>
      </node>
      <node defType="com.stambia.file.field" id="_lN_SMXpREe6QncsbWkl3eg" name="F6" position="6">
        <attribute defType="com.stambia.file.field.size" id="_lN_SMnpREe6QncsbWkl3eg" value="63"/>
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
        <attribute defType="com.stambia.file.field.type" id="_lN_5O3pREe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_lN_5PHpREe6QncsbWkl3eg" value="F1"/>
      </node>
      <node defType="com.stambia.file.field" id="_lN_5PXpREe6QncsbWkl3eg" name="F5" position="5">
        <attribute defType="com.stambia.file.field.size" id="_lN_5PnpREe6QncsbWkl3eg" value="54"/>
        <attribute defType="com.stambia.file.field.type" id="_lN_5P3pREe6QncsbWkl3eg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_lN_5QHpREe6QncsbWkl3eg" value="F5"/>
      </node>
      <node defType="com.stambia.file.propertyField" id="_6BmfBH1GEe6F_fnQESD-eA" name="file_name">
        <attribute defType="com.stambia.file.propertyField.property" id="_7pIdgH1GEe6F_fnQESD-eA" value="file_name"/>
      </node>
      <node defType="com.stambia.file.field" id="_TyZ3sH1UEe6F_fnQESD-eA" name="C7" position="7">
        <attribute defType="com.stambia.file.field.physicalName" id="_Tyc7AH1UEe6F_fnQESD-eA" value="C7"/>
        <attribute defType="com.stambia.file.field.type" id="_Tyc7AX1UEe6F_fnQESD-eA" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_Tyc7An1UEe6F_fnQESD-eA" value="50"/>
      </node>
      <node defType="com.stambia.file.field" id="_T2YYwH1UEe6F_fnQESD-eA" name="C8" position="8">
        <attribute defType="com.stambia.file.field.physicalName" id="_T2YYwX1UEe6F_fnQESD-eA" value="C8"/>
        <attribute defType="com.stambia.file.field.type" id="_T2YYwn1UEe6F_fnQESD-eA" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_T2YYw31UEe6F_fnQESD-eA" value="50"/>
      </node>
      <node defType="com.stambia.file.field" id="_T40BsH1UEe6F_fnQESD-eA" name="C9" position="9">
        <attribute defType="com.stambia.file.field.physicalName" id="_T40BsX1UEe6F_fnQESD-eA" value="C9"/>
        <attribute defType="com.stambia.file.field.type" id="_T40Bsn1UEe6F_fnQESD-eA" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_T40Bs31UEe6F_fnQESD-eA" value="50"/>
      </node>
      <node defType="com.stambia.file.field" id="_T7BBIH1UEe6F_fnQESD-eA" name="C10" position="10">
        <attribute defType="com.stambia.file.field.physicalName" id="_T7BoMH1UEe6F_fnQESD-eA" value="C10"/>
        <attribute defType="com.stambia.file.field.type" id="_T7BoMX1UEe6F_fnQESD-eA" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_T7BoMn1UEe6F_fnQESD-eA" value="50"/>
      </node>
      <node defType="com.stambia.file.field" id="_U4VlAH1UEe6F_fnQESD-eA" name="C11" position="11">
        <attribute defType="com.stambia.file.field.physicalName" id="_U4WMEH1UEe6F_fnQESD-eA" value="C11"/>
        <attribute defType="com.stambia.file.field.type" id="_U4WMEX1UEe6F_fnQESD-eA" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_U4WMEn1UEe6F_fnQESD-eA" value="50"/>
      </node>
      <node defType="com.stambia.file.field" id="_U8qrYH1UEe6F_fnQESD-eA" name="C12" position="12">
        <attribute defType="com.stambia.file.field.physicalName" id="_U8rScH1UEe6F_fnQESD-eA" value="C12"/>
        <attribute defType="com.stambia.file.field.type" id="_U8rScX1UEe6F_fnQESD-eA" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_U8rScn1UEe6F_fnQESD-eA" value="50"/>
      </node>
      <node defType="com.stambia.file.field" id="_gLp24H1VEe6F_fnQESD-eA" name="C13" position="13">
        <attribute defType="com.stambia.file.field.physicalName" id="_gLrFAH1VEe6F_fnQESD-eA" value="C13"/>
        <attribute defType="com.stambia.file.field.type" id="_gLrFAX1VEe6F_fnQESD-eA" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_gLrFAn1VEe6F_fnQESD-eA" value="50"/>
      </node>
    </node>
  </node>
</md:node>