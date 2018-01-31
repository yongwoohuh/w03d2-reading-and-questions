# W03D2 Reading and Questions
Q1.
Think about your favourite apps. Where do they use tableviews? Do you use any apps regularly that don't have tableviews?
A:no

Q2.
What are static table views and when would you use them?
A: When the content in the cell is static. You will use static table views in settings.

Q3.
a. What is the class hierarchy of a UITableView? IE what classes does it inherit from and what protocols does it conform to?
* Inherits From :
	UIScrollView
		UIView
			UIResponder
				NSObject
* Conforms To:
NSCoding
UIDataSourceTranslating

b. How does it compare to the class hierarchy of UICollectionView?
A:UICollectionView does not conform to NSCoding
Q4. How do you make a tableview that moves horizontally rather than vertically?
A: use a UICollectionView

Q5.
What happens when I comment out this line of code?
[tableView deseletRowAtIndexPath:[tableView indexPathForSelectedRow] animated:NO];
A:deselecting a row would not work.