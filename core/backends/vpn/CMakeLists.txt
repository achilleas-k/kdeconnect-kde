
set(kded_kdeconnect_SRCS
    ${kded_kdeconnect_SRCS}

    backends/vpn/vpnlinkprovider.cpp
    backends/vpn/vpndevicelink.cpp
    backends/vpn/uploadjob.cpp
    backends/vpn/downloadjob.cpp
    backends/vpn/socketlinereader.cpp

    PARENT_SCOPE
)
