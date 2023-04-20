# Support_Vector_Machine
# When i get my "X" and "y" predicted I can import "train_test_split" and get "train" and "test" set 
# Then from preprocessing I get "StandardScaler" because I need to make "feature scaling"
# I use method "fit_transform" on my "X_train" """X_train = sc.fit_transform(X_train)""" and "transform" on "X_test" """X_test = sc.transform(X_test)"""
# Next i get my "SVC" model and use parameter "kernel" at "linear", then I train my model """classifier.fit(X_train, y_train)"""
# Then I check predictions """print(classifier.predict(sc.transform([[30,87000]])))"""
# Prepare "y_pred" with my "X_test" """y_pred = classifier.predict(X_test)""" and print it "reshape into columns for more clarity
