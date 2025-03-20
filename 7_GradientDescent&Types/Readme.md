What exactly is Gradient Descent?

Gradient Descent is an optimization algorithm used to minimize the loss function and update model parameters in machine learning. There are three main types:

1️⃣ Batch Gradient Descent (BGD) 📌 Updates parameters using the entire dataset at each step.

🔹 How it works:

Computes gradients over the entire dataset.

Updates weights only once per epoch (after all samples are processed).

✅ Pros:
✔ More stable updates, converges smoothly.

✔ Suitable for small datasets.

❌ Cons:

❌ Slow for large datasets (expensive computations).

❌ Can get stuck in local minima.

2️⃣ Stochastic Gradient Descent (SGD) 📌 Updates parameters after every single training example (one at a time).

🔹 How it works:

Randomly selects one sample and updates weights immediately.

Faster but more noisy updates.

✅ Pros: 
✔ Works well for large datasets.

✔ Can escape local minima due to randomness.

❌ Cons:

❌ High variance in updates (can oscillate).

❌ Convergence is less stable.

3️⃣ Mini-Batch Gradient Descent 📌 Updates parameters using a small batch of training examples.

🔹 How it works:

A compromise between Batch GD and SGD.

Divides data into mini-batches (e.g., 32 or 64 samples per batch). Computes gradients for each mini-batch and updates weights.

✅ Pros: 
✔ Faster than Batch GD and less noisy than SGD.

✔ Efficient for large datasets.

✔ Takes advantage of vectorized operations (faster computation).

❌ Cons:

❌ Requires hyperparameter tuning (choosing the batch size).

********************************************************

✔ Batch GD: Best for small datasets, but slow for large ones.

✔ SGD: Works well for big datasets, but updates can be unstable.

✔ Mini-Batch GD: The best compromise between speed and stability.

************************************************
