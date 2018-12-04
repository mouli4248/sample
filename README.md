plugins {
    id 'scala'
}

repositories {
    mavenCentral()
    maven {
        url "http://conjars.org/repo"
    }
    maven {
        url "http://repo.spring.io/plugins-release"
    }
}

dependencies {
    compile 'org.apache.spark:spark-sql_2.11:2.2.1'
    compile 'org.elasticsearch:elasticsearch-spark-20_2.11:5.4.3'
    compile 'org.scala-lang:scala-library:2.11.8'
    testCompile 'org.scalatest:scalatest_2.11:3.0.4'
    testCompile 'junit:junit:4.12'
}
