How to reproduce:

1) Run 

    > ./gradlew assemble

2) Expected output

    > Cannot add task ':mylibrary:prepareComAndroidSupportRecyclerviewV72311Library'

Removing the RecyclerView dependency in `mylibrary/build.gradle` fixes the problem, but 
indicate that it works for JAR's but not AAR's.

