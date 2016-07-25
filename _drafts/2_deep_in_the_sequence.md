#2 Deep in the Sequence

## Visaulizing Observables

To Help developers understand operators in an easy way, we'll use a standard visual repersentation for sequences, called *marble diagram*. They visaully repressent asynchronous data streams, and you will find them in every resources for RxJS

## Basic Sequnece Operators

- Map
- Filter
- Reduce
	- Aggeregate Operators : Aggregate opertors process a sequence and return a single value, Rx.Observable.first takes an Observable and an optional predicate function and returns the first element that satisfies the condition in the predicate. Every aggregate operator can be implemented by using only *reduce*
		- average
- flatMap

## Canceling Sequence
- Explicit Cancellation: Tbe Disposable
- Implicit Cancellation: By Operator
	- range
	- take
- Observables That Wrap External APIs

## Hadling Errors
- The `onError` Handler
- Catching Errors
- Retrying Sequences
- Making a Real-Time Earthquzke Visaulizer


|Name|Default behavior|Description|   
|---|:---:|:---|
|Rx.observable.from|Synchronus|#|
|Rx.observable.range|Synchronus|#|
|Rx.observable.interval|Asynchronus|#|
|Rx.observable.distinct|Same as the Observable it filters|distinct let us use a function that sepcifies the comparision method.|

## Wrapping up








	
