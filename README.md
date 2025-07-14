<?xml version="1.0" encoding="utf-8"?>
<!--
https://go.microsoft.com/fwlink/?LinkID=208121.
-->
<Project>
	<PropertyGroup>
		<ApplicationRevision>244</ApplicationRevision>
		<ApplicationVersion>1.0.0.244</ApplicationVersion>
		<BootstrapperEnabled>True</BootstrapperEnabled>
		<Configuration>Release</Configuration>
		<CreateDesktopShortcut>True</CreateDesktopShortcut>
		<CreateWebPageOnPublish>True</CreateWebPageOnPublish>
		<GenerateManifests>true</GenerateManifests>
		<Install>True</Install>
		<InstallFrom>Web</InstallFrom>
		<InstallUrl>http://172.18.30.6:1000/</InstallUrl>
		<IsRevisionIncremented>False</IsRevisionIncremented>
		<IsWebBootstrapper>True</IsWebBootstrapper>
		<MapFileExtensions>True</MapFileExtensions>
		<OpenBrowserOnPublish>False</OpenBrowserOnPublish>
		<Platform>Any CPU</Platform>
		<PublishDir>bin\Release\netcoreapp3.1\app.publish\</PublishDir>
		<PublishUrl>D:\Web\DDM_MES_DEV\</PublishUrl>
		<PublishProtocol>ClickOnce</PublishProtocol>
		<PublishReadyToRun>False</PublishReadyToRun>
		<PublishSingleFile>False</PublishSingleFile>
		<SelfContained>False</SelfContained>
		<SignatureAlgorithm>(없음)</SignatureAlgorithm>
		<SignManifests>False</SignManifests>
		<TargetFramework>netcoreapp3.1</TargetFramework>
		<UpdateEnabled>True</UpdateEnabled>
		<UpdateMode>Foreground</UpdateMode>
		<UpdateRequired>False</UpdateRequired>
		<WebPageFileName>Publish.html</WebPageFileName>
		<CreateDesktopShortcut>True</CreateDesktopShortcut>
		<ProductName>DDM MES</ProductName>
		<PublisherName>대동모빌리티</PublisherName>
		<SuiteName>DDM MES</SuiteName>
		<TargetCulture>ko-KR</TargetCulture>
		<SkipPublishVerification>false</SkipPublishVerification>
	</PropertyGroup>
	<ItemGroup>
		<PublishFile Include="DDM.ico">
			<Group>
			</Group>
			<TargetPath>
			</TargetPath>
			<PublishState>Include</PublishState>
			<IncludeHash>true</IncludeHash>
			<FileType>File</FileType>
		</PublishFile>
		<PublishFile Include="DevHistory.txt">
			<Group>
			</Group>
			<TargetPath>
			</TargetPath>
			<PublishState>Include</PublishState>
			<IncludeHash>true</IncludeHash>
			<FileType>File</FileType>
		</PublishFile>
		<PublishFile Include="LogWriter\CSLogTableAlter.txt">
			<Group>
			</Group>
			<TargetPath>
			</TargetPath>
			<PublishState>Include</PublishState>
			<IncludeHash>true</IncludeHash>
			<FileType>File</FileType>
		</PublishFile>
		<PublishFile Include="LogWriter\TABLECREATEION.txt">
			<Group>
			</Group>
			<TargetPath>
			</TargetPath>
			<PublishState>Include</PublishState>
			<IncludeHash>true</IncludeHash>
			<FileType>File</FileType>
		</PublishFile>
		<PublishFile Include="sqlSample.xml">
			<Group>
			</Group>
			<TargetPath>
			</TargetPath>
			<PublishState>Include</PublishState>
			<IncludeHash>true</IncludeHash>
			<FileType>File</FileType>
		</PublishFile>
		<PublishFile Include="Storage\SQLSTORE_SQL.txt">
			<Group>
			</Group>
			<TargetPath>
			</TargetPath>
			<PublishState>Include</PublishState>
			<IncludeHash>true</IncludeHash>
			<FileType>File</FileType>
		</PublishFile>
	</ItemGroup>
	<ItemGroup>
		<Content Include="config\**\*" />
	</ItemGroup>
	<ItemGroup>
		<Content Include="alert\**\*" />
	</ItemGroup>
	<ItemGroup>
		<BootstrapperPackage Include="Microsoft.NetCore.DesktopRuntime.3.1.x64">
			<Install>true</Install>
			<ProductName>.NET?Core?데스크톱?런타임 3.1.32 (x64)</ProductName>
		</BootstrapperPackage>
	</ItemGroup>
</Project>