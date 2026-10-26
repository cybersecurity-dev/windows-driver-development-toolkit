<div align="center">
    <p align="center">
        <a href="https://github.com/cybersecurity-dev/awesome-windows-driver-development">
          <img width="20%" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/Windows.svg" />
        </a>
    </p>

```mermaid
ishikawa-beta
    Competent Windows Driver Toolkit User
        Phase 1 - Environment
            Install Visual Studio
            Install Windows SDK
            Install Windows Driver Kit
            Select C plus plus workload
            Verify kit compatibility
            Configure source repository

        Phase 2 - Test<br/>Infrastructure
            Create isolated test VM
            Configure test signing
            Configure debug transport
            Enable kernel debugging
            Create clean snapshots
            Prepare recovery procedure

        Phase 3 - Driver<br/>Project
            Select driver template
            Select KMDF UMDF or WDM
            Configure target architecture
            Configure target operating system
            Add WDK headers
            Add driver libraries

        Phase 4 - Build<br/>Tools
            Configure MSBuild
            Compile source files
            Link SYS binary
            Review warnings
            Generate PDB symbols
            Preserve reproducible artifacts

        Phase 5 - Package<br/>Tools
            Create INF file
            Validate hardware IDs
            Validate service configuration
            Generate catalog
            Apply test signature
            Assemble deployable package

        Phase 6 - Static<br/>Verification
            Use compiler warnings
            Run code analysis
            Apply SAL annotations
            Validate driver APIs
            Verify INF syntax
            Review architecture assumptions

        Phase 7 - Deployment
            Stage package in Driver Store
            Install driver
            Inspect device status
            Update package
            Remove package
            Test rollback

        Phase 8 - WinDbg
            Configure Microsoft symbols
            Configure private symbols
            Connect debugger
            Set source path
            Set driver breakpoints
            Inspect modules and threads

        Phase 9 - Kernel<br/>Diagnostics
            Inspect call stacks
            Inspect registers
            Inspect memory
            Inspect device objects
            Inspect WDF objects
            Analyze bug checks

        Phase 10 - Tracing
            Add WPP tracing
            Configure trace providers
            Capture ETW events
            Correlate traces and requests
            Preserve timestamps
            Export diagnostic evidence

        Phase 11 - Driver Verifier
            Select driver under test
            Select verification rules
            Restart target
            Execute stress workload
            Capture verifier failures
            Disable verifier safely

        Phase 12 - Functional<br/>Testing
            Test successful requests
            Test invalid requests
            Test cancellation
            Test timeouts
            Test concurrent access
            Test resource cleanup

        Phase 13 - Lifecycle<br/>Testing
            Test device installation
            Test device removal
            Test surprise removal
            Test sleep and resume
            Test update
            Test rollback

        Phase 14 - Release
            Review security
            Create release build
            Sign final package
            Validate clean installation
            Archive symbols
            Publish documentation
```

# **`WDDT`** | Windows Driver Development Toolkit
</div>

[![Windows](https://custom-icon-badges.demolab.com/badge/Windows-0078D6?style=for-the-badge&logo=windows11&logoColor=white)]()
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]() 
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)]()


```mermaid
treemap-beta
    "Windows Driver Development Toolkit"
        "Development Environment"
            "Visual Studio": 8
            "Windows SDK": 5
            "Windows Driver Kit": 9
            "Enterprise WDK": 3

        "Source Development"
            "Driver Templates": 5
            "WDK Headers": 5
            "WDK Libraries": 5
            "Driver Samples": 4
            "WPP Tracing": 4

        "Build and Package"
            "MSBuild": 5
            "Compiler and Linker": 6
            "INF Tools": 5
            "Catalog Tools": 4
            "Signing Tools": 5

        "Deployment"
            "PnPUtil": 4
            "Driver Store": 4
            "Device Inspection": 4
            "Test Signing": 4

        "Debugging"
            "WinDbg": 9
            "Symbol Tools": 4
            "Crash Dumps": 5
            "Debugger Extensions": 4
            "Trace Analysis": 4

        "Verification"
            "Driver Verifier": 8
            "Static Analysis": 5
            "Functional Tests": 5
            "Stress Tests": 5
            "PnP and Power Tests": 5
```

##

### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/windows-driver-development-toolkit/graphs/contributors)!

[🔼 Back to top](#wddt--windows-driver-development-toolkit)
