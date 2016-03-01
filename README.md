# Example project for the Instrumental reporter for Dropwizard
This is simple example application using the [Instrumental reporter for Dropwizard](https://github.com/egineering-llc/metrics-instrumental).

After checking out this repo, run

`mvn clean dependency:copy-dependencies package`

then

`java -cp target/egineering_dropwizard_client-1.0-SNAPSHOT.jar:target/dependency/* com.instrumental_java_client_test.expectedbehavior.app.App`

The example sends metric directly to Instrumental and also through a registry. You can view all metrics sent to Instrumental from this example by making a graph with the query `instrumental.java.*`

## More Help?
If you need more help or examples, contact [support@instrumentalapp.com](support@instrumentalapp.com).
