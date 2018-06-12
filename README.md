# solr-core
sample solr core for jease

For run migration command from any Object Database to Solr you can use jease builded lib with this command:

```
 java -cp target/ROOT/WEB-INF/classes:target/ROOT/WEB-INF/lib/* jfix.db4o.engine.migration.AnytoSolr http://localhost:8983/solr/jease
 ```
 
 Before use above command you must start solr.
 
 
 Installing Solr

For the purposes of this tutorial, I'll assume you're on a Linux or Mac environment.

You should also have JDK 6 or above installed.

wget http://www-us.apache.org/dist/lucene/solr/7.3.1/solr-7.3.1.tgz

tar -zxvf solr-7.3.1.tgz

Starting Solr

cd solr/bin

$./solr start
