SET(OrmSrc 
	Column.cc
	DbHelper.cc
	DbResult.cc
	Expr.cc
	MessageField.cc
)

ADD_LIBRARY(Orm ${OrmSrc})