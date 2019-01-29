Run 5 times, index from 0 to 4:
{
    run 10 times: 
    {
        python train_gpu.py --cross_val_index={{index}} 
        => note the result

        python train_gpu.py --cross_val_index={{index}} --schedule=evaluate --is_test
        => note the result 
    }
}
