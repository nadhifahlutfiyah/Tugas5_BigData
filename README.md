# Tugas5_BigData

## Penjelasan Kode Program

1. mylist , myschema : dua variabel dalam Python yang digunakan untuk membuat DataFrame di PySpark. mylist adalah daftar item, sedangkan myschema adalah daftar string yang mendefinisikan nama kolom DataFrame.

2. spark.createDataFrame : metode PySpark yang digunakan untuk membuat DataFrame dari data yang diberikan.

3. parallelize : metode PySpark yang digunakan untuk membuat RDD dari data yang diberikan, sedangkan toDF adalah metode yang digunakan untuk mengonversi RDD menjadi DataFrame.

4. hadoop, fs, put : perintah untuk mengunggah file ke sistem file Hadoop.

5. pyspark.sql, SQLContext, createOrReplaceTempView, show : komponen PySpark yang digunakan untuk memanipulasi dan menampilkan data dalam format DataFrame.

6. textFile, map, lambda, strip, StructField, StringType : komponen PySpark yang digunakan untuk membaca dan memproses data teks.

7. spark.read.format, jdbc, options, load : komponen PySpark yang digunakan untuk membaca data dari sumber eksternal seperti database.

8. show : metode PySpark yang digunakan untuk menampilkan data dalam format DataFrame.

9. collect, rdd, take : metode PySpark yang digunakan untuk mengambil data dari RDD dan menampilkannya dalam format yang sesuai.

10. makeRDD, Seq, createDataset : metode PySpark yang digunakan untuk membuat RDD dan Dataset dari data yang diberikan.

11. filter : PySpark yang digunakan untuk menyaring data dalam RDD atau DataFrame.

12. as, toDF, first : metode PySpark yang digunakan untuk mengonversi data ke format DataFrame dan melakukan operasi di dalamnya.

13. listDatabases, listTables, listFunctions, isCached, select : metode PySpark yang digunakan untuk memanipulasi dan mengambil data dari database dalam format DataFrame.

14. read , text : metode PySpark yang digunakan untuk membaca data teks.

15. load, json, format, printSchema : metode PySpark yang digunakan untuk membaca dan menampilkan data dalam format JSON.

16. write , save : metode PySpark yang digunakan untuk  menyimpan data dalam format yang ditentukan.

17. parquet : format untuk menyimpan data tabular dengan efisiensi kompresi yang tinggi dalam Hadoop.

18. Options : untuk menyediakan konfigurasi tambahan ketika membaca data.

19. inferSchema : untuk menentukan apalah schema dari DataFrame harus diinfer dahulu dari data sumber atau ditentukan langsung secara eksplisit oleh pengguna.

20. csv : menunjukkan format sumber data.

21. header : menunjukkan sumber data memiliki header yang digunakan untuk nama kolom DataFrame.

22. codec : digunakan untuk membaca data yang dienkripsi atau dikompresi.
