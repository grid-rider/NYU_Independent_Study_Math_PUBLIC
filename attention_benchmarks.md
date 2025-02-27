Running extreme attention mechanism benchmarks over varying sequence lengths...


Benchmarking sequence length: 256
  -> Method: xformers
     Average forward pass time: 0.0035 sec
     System Resources: CPU Usage: 7.0%, Memory Usage: 16.5%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  -> Method: performer
     Average forward pass time: 0.0044 sec
     System Resources: CPU Usage: 2.5%, Memory Usage: 16.5%, GPU Memory Allocated: 24.9 MB, Reserved: 2506.0 MB
  -> Method: nystrom
     Average forward pass time: 0.0059 sec
     System Resources: CPU Usage: 2.0%, Memory Usage: 16.5%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB

Benchmarking sequence length: 512
  -> Method: xformers
     Average forward pass time: 0.0044 sec
     System Resources: CPU Usage: 2.0%, Memory Usage: 16.5%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  -> Method: performer
     Average forward pass time: 0.0064 sec
     System Resources: CPU Usage: 2.0%, Memory Usage: 16.5%, GPU Memory Allocated: 24.9 MB, Reserved: 2506.0 MB
  -> Method: nystrom
     Average forward pass time: 0.0071 sec
     System Resources: CPU Usage: 2.0%, Memory Usage: 16.5%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB

Benchmarking sequence length: 1024
  -> Method: xformers
     Average forward pass time: 0.0099 sec
     System Resources: CPU Usage: 3.5%, Memory Usage: 16.6%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  -> Method: performer
     Average forward pass time: 0.0123 sec
     System Resources: CPU Usage: 37.3%, Memory Usage: 16.6%, GPU Memory Allocated: 24.9 MB, Reserved: 2506.0 MB
  -> Method: nystrom
     Average forward pass time: 0.0121 sec
     System Resources: CPU Usage: 13.0%, Memory Usage: 16.5%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB

Benchmarking sequence length: 2048
  -> Method: xformers
     Average forward pass time: 0.0270 sec
     System Resources: CPU Usage: 9.1%, Memory Usage: 16.3%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  -> Method: performer
     Average forward pass time: 0.0244 sec
     System Resources: CPU Usage: 1.5%, Memory Usage: 16.3%, GPU Memory Allocated: 24.9 MB, Reserved: 2506.0 MB
  -> Method: nystrom
     Average forward pass time: 0.0176 sec
     System Resources: CPU Usage: 4.0%, Memory Usage: 16.4%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB

Benchmarking sequence length: 4096
  -> Method: xformers
     Average forward pass time: 0.0794 sec
     System Resources: CPU Usage: 25.6%, Memory Usage: 16.5%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  -> Method: performer
     Average forward pass time: 0.0514 sec
     System Resources: CPU Usage: 2.0%, Memory Usage: 16.6%, GPU Memory Allocated: 24.9 MB, Reserved: 2506.0 MB
  -> Method: nystrom
     Average forward pass time: 0.0355 sec
     System Resources: CPU Usage: 2.5%, Memory Usage: 16.3%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB

Benchmarking sequence length: 8192
  -> Method: xformers
     Average forward pass time: 0.2585 sec
     System Resources: CPU Usage: 2.0%, Memory Usage: 16.4%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  -> Method: performer
     Average forward pass time: 0.0993 sec
     System Resources: CPU Usage: 2.5%, Memory Usage: 16.4%, GPU Memory Allocated: 24.9 MB, Reserved: 2506.0 MB
  -> Method: nystrom
     Average forward pass time: 0.0673 sec
     System Resources: CPU Usage: 5.0%, Memory Usage: 16.5%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB

Benchmarking sequence length: 16384
  -> Method: xformers
     Average forward pass time: 0.9018 sec
     System Resources: CPU Usage: 3.5%, Memory Usage: 16.4%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  -> Method: performer
     Average forward pass time: 0.1922 sec
     System Resources: CPU Usage: 2.5%, Memory Usage: 16.4%, GPU Memory Allocated: 24.9 MB, Reserved: 2506.0 MB
  -> Method: nystrom
     Average forward pass time: 0.1334 sec
     System Resources: CPU Usage: 38.4%, Memory Usage: 16.3%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
Plot 'attention_benchmarks.png' saved.


Detailed Summary of Average Forward Pass Times and Resource Logs:

Method: xformers
  Seq Length   256: Time = 0.0035 sec | CPU Usage: 7.0%, Memory Usage: 16.5%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  Seq Length   512: Time = 0.0044 sec | CPU Usage: 2.0%, Memory Usage: 16.5%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  Seq Length  1024: Time = 0.0099 sec | CPU Usage: 3.5%, Memory Usage: 16.6%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  Seq Length  2048: Time = 0.0270 sec | CPU Usage: 9.1%, Memory Usage: 16.3%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  Seq Length  4096: Time = 0.0794 sec | CPU Usage: 25.6%, Memory Usage: 16.5%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  Seq Length  8192: Time = 0.2585 sec | CPU Usage: 2.0%, Memory Usage: 16.4%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  Seq Length 16384: Time = 0.9018 sec | CPU Usage: 3.5%, Memory Usage: 16.4%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB

Method: performer
  Seq Length   256: Time = 0.0044 sec | CPU Usage: 2.5%, Memory Usage: 16.5%, GPU Memory Allocated: 24.9 MB, Reserved: 2506.0 MB
  Seq Length   512: Time = 0.0064 sec | CPU Usage: 2.0%, Memory Usage: 16.5%, GPU Memory Allocated: 24.9 MB, Reserved: 2506.0 MB
  Seq Length  1024: Time = 0.0123 sec | CPU Usage: 37.3%, Memory Usage: 16.6%, GPU Memory Allocated: 24.9 MB, Reserved: 2506.0 MB
  Seq Length  2048: Time = 0.0244 sec | CPU Usage: 1.5%, Memory Usage: 16.3%, GPU Memory Allocated: 24.9 MB, Reserved: 2506.0 MB
  Seq Length  4096: Time = 0.0514 sec | CPU Usage: 2.0%, Memory Usage: 16.6%, GPU Memory Allocated: 24.9 MB, Reserved: 2506.0 MB
  Seq Length  8192: Time = 0.0993 sec | CPU Usage: 2.5%, Memory Usage: 16.4%, GPU Memory Allocated: 24.9 MB, Reserved: 2506.0 MB
  Seq Length 16384: Time = 0.1922 sec | CPU Usage: 2.5%, Memory Usage: 16.4%, GPU Memory Allocated: 24.9 MB, Reserved: 2506.0 MB

Method: nystrom
  Seq Length   256: Time = 0.0059 sec | CPU Usage: 2.0%, Memory Usage: 16.5%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  Seq Length   512: Time = 0.0071 sec | CPU Usage: 2.0%, Memory Usage: 16.5%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  Seq Length  1024: Time = 0.0121 sec | CPU Usage: 13.0%, Memory Usage: 16.5%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  Seq Length  2048: Time = 0.0176 sec | CPU Usage: 4.0%, Memory Usage: 16.4%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  Seq Length  4096: Time = 0.0355 sec | CPU Usage: 2.5%, Memory Usage: 16.3%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  Seq Length  8192: Time = 0.0673 sec | CPU Usage: 5.0%, Memory Usage: 16.5%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB
  Seq Length 16384: Time = 0.1334 sec | CPU Usage: 38.4%, Memory Usage: 16.3%, GPU Memory Allocated: 22.9 MB, Reserved: 2506.0 MB