在当前项目根目录 执行安排jar 到github

mvn install:install-file -DgroupId=com.demo.starter -DartifactId=helloworld -Dversion=0.0.1-SNAPSHOT -Dfile=helloworld-0.0.1-SNAPSHOT.jar -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=.  -DcreateChecksum=true
