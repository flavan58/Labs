# Labs
VM-Azure-Dio
Abrir o Cloud Shell
New-AzVm `
    -ResourceGroupName 'LABAZ104' `
    -Name 'teste-vm06' `
    -Location 'West Europe' `
    -Image 'MicrosoftWindowsServer:WindowsServer:2022-datacenter-azure-edition:latest' `
    -VirtualNetworkName 'myVnet' `
    -SubnetName 'mySubnet' `
    -SecurityGroupName 'myNetworkSecurityGroup' `
    -PublicIpAddressName 'myPublicIpAddress' `
    -OpenPorts 80,3389
