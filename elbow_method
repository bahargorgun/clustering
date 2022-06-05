distortions = []
for i in range(1,5):
    km = KMeans(n_clusters=i,
    init='k-means++',
    n_init=10,
    max_iter=300,
    random_state=0)

    km.fit(X)
    distortions.append(km.inertia_)
plt.plot(range(1,5),distortions,marker='o')    
plt.xlabel('Number of clusters')
plt.ylabel('Distortion')
plt.show()
