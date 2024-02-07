import matplotlib.pyplot as plt

# Define time intervals
t_a = 10  # Time for acceleration (s)
t_c = 20  # Time for constant velocity (s)
t_d = 2   # Time for deceleration (s)

# Define velocities
v_i = 0    # Initial velocity (m/s)
v_f = 50   # Final velocity (m/s)

# Define time points
time_points = [0, t_a, t_a + t_c, t_a + t_c + t_d]
velocity_points = [v_i, v_f, v_f, 0]

# Plot the graph
plt.plot(time_points, velocity_points, marker='o', linestyle='-')
plt.title('Velocity-Time Graph of Car Motion')
plt.xlabel('Time (s)')
plt.ylabel('Velocity (m/s)')
plt.grid(True)
plt.show()
