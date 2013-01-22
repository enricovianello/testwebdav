testwebdav
==========

uses jackrabbit libraries to test a webdav server with anonymous authentication; specify gridhttps hostname as executable argument

TO USE:

cd <project-dir>

mvn clean install

java -jar target/testclient.jar <gridhttps-hostname>
