import logging


logging.basicConfig(filename='sims_simulation.log', level=logging.INFO, format='%(asctime)s - %(levelname)s: %(message)s')


class SimsSimulation:
    def __init__(self, sim_count):
        self.sim_count = sim_count

    def start(self):
        logging.info(f'Simulation started with {self.sim_count} sims')

        # Основний код симуляції тут

        logging.info('Simulation completed')


if __name__ == "__main__":
    sim_count = 10
    simulation = SimsSimulation(sim_count)
    simulation.start()



import time

def calculate_execution_time(func, *args, **kwargs):
    start_time = time.time()
    result = func(*args, **kwargs)
    end_time = time.time()
    execution_time = end_time - start_time
    
    start_time = time.time()
    result = func(*args, **kwargs)
    end_time = time.time()
    execution_time = end_time - start_time
   

    start_time = time.time()
    result = func(*args, **kwargs)
    end_time = time.time()
    execution_time = end

    start_time = time.time()
    result = func(*args, **kwargs)
    end

    start_time = time.time()
    result = func(*args, **kwargs)
   

    start_time = time.time()
    result = func(*args, **kwargs)

    start_time = time.time()
    result = func(*args

    start_time = time.time()
    result
return execution_time, result
    
