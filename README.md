<jnlp spec="1.0+" codebase="http://108.181.18.18:80/">
  <information>
    <title>ATEN Java iKVM Viewer</title>
    <vendor>ATEN</vendor>
    <description>Java Web Start Application</description>
  </information>

  <security>
   <all-permissions/>
  </security>

  <resources>
    <property name="jnlp.packEnabled" value="true"/>
    <property name="jnlp.versionEnabled" value="true"/>
    <j2se version="1.6.0+" java-vm-args="-Xmx128M -Xms128M -Xss1M -XX:PermSize=32M -XX:MaxPermSize=32M"/>
    <jar href="iKVM__V1.69.21.0x0.jar" download="eager" main="true"/>
  </resources>

  <resources os="Windows" arch="x86">
    <nativelib href="libwin_x86__V1.0.5.jar" download="eager"/>
  </resources>
  <resources os="Windows" arch="x86_64">
    <nativelib href="libwin_x86_64__V1.0.5.jar" download="eager"/>
  </resources>
  <resources os="Windows" arch="amd64">
    <nativelib href="libwin_x86_64__V1.0.5.jar" download="eager"/>
  </resources>

  <resources os="Linux" arch="i386">
    <nativelib href="liblinux_x86__V1.0.5.jar" download="eager"/>
  </resources>
  <resources os="Linux" arch="x86">
    <nativelib href="liblinux_x86__V1.0.5.jar" download="eager"/>
  </resources>
  <resources os="Linux" arch="x86_64">
    <nativelib href="liblinux_x86_64__V1.0.5.jar" download="eager"/>
  </resources>
  <resources os="Linux" arch="amd64">
    <nativelib href="liblinux_x86_64__V1.0.5.jar" download="eager"/>
  </resources>

  <resources os="Mac OS X" arch="x86_64">
    <nativelib href="libmac_x86_64__V1.0.5.jar" download="eager"/>
  </resources>

  <resources os="SunOS" arch="sparc">
    <nativelib href="libsun_SPARC__V1.0.5.jar" download="eager"/>
  </resources>

  <application-desc main-class="tw.com.aten.ikvm.KVMMain">
    <argument>108.181.18.18</argument>
    <argument>dcijzeticteggtxh</argument>
    <argument>dcijzeticteggtxh</argument>
	<argument>null</argument>
    <argument>5900</argument>
    <argument>623</argument>
    <argument>2</argument>
    <argument>0</argument>
  </application-desc>
</jnlp>
