# datasets
This is the collection of datasets which can be read with the help of csq2
#reading data<br />
main:<br />
&nbsp;pd::table tb;<br />
&nbsp;tb.load_data("iris.data",{"sepal length","sepal width","petal lenght","petal width","species"});<br />
endmain
