# my_stock

plt.figure(figsize=(20,40))
for i, col in enumerate(categorical_columns) :
    plt.subplot(5,5, i+1)
    plt.hist(train_df[col], bins=10)
    plt.title(col)
plt.show()
