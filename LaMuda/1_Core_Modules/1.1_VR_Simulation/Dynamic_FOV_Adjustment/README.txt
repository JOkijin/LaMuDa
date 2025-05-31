1.1_VR_Simulation/
├── Dynamic_FOV_Adjustment/
│   ├── fov_controller.py            # 动态视场调节核心算法 
│   ├── vertigo_predictor.py         # 眩晕风险模型 
│   └── tests/
│       ├── test_fov_adjustment.py 
│       └── test_vertigo_model.py 
├── Varjo_SDK_Integration/
│   ├── varjo_interface.py           # 头盔硬件接口
│   ├── foveated_rendering.py        # 注视点渲染实现
│   └── docs/
│       ├── setup_guide.md           # Varjo硬件设置指南 
│       └── api_reference.md  
├── EEG_Monitor/
│   ├── openbci_adapter.py           # OpenBCI集成适配器
│   ├── fatigue_analyzer.py          # θ波疲劳分析
│   └── config/
│       └── eeg_calibration.yaml     # 脑电校准参数
├── simulation_manager.py            # 主控制模块
├── requirements.txt                 # 依赖库 
└── Dockerfile                      # 容器化部署