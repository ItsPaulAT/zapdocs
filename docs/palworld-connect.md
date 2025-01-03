---
id: palworld-connect
title: "Palworld: Connect to Palworld Server"
description: Information about connecting to a Palworld server from ZAP-Hosting - ZAP-Hosting.com documentation
sidebar_label: Connect to Server
services:
  - gameserver
---

import YouTube from '@site/src/components/YouTube/YouTube';
import InlineVoucher from '@site/src/components/InlineVoucher';

## Introduction

In this guide, we will explore how to connect to your Palworld server. We recommend configurating the server to your likings beforehand, learn more about this through our [Server Configuration](palworld-configuration.md) guide.

:::tip
We have a separate **Palword (Xbox)** game version now available on our Gameservers, which allows you to play on Xbox/Microsoft Store game versions. Check out our [Game Change](gameserver-gameswitch.md) guide to learn how to easily switch your game. Make sure to backup your saves as always.
:::

<YouTube videoId="SDZC4-FEdNM" imageSrc="https://screensaver01.zap-hosting.com/index.php/s/eA3xonLFkB4x3G6/preview" title="Setup Palworld server in just a MINUTE!" description="Feel like you understand better when you see things in action? We’ve got you! Dive into our video that breaks it all down for you. Whether you're in a rush or just prefer to soak up information in the most engaging way possible!"/>

<InlineVoucher />

## Obtaining Server IP

Firstly, you need to know the IP and Port of your Palworld server in order to be able to direct connect. Simply head over to your [ZAP-Hosting webinterface](https://zap-hosting.com/en/customer/) on the site, and have the full IP and Port on hand.

![](https://github.com/zaphosting/docs/assets/42719082/62bcad5b-064c-45cd-a7f0-406a1148b15c)

If you are running your Palworld server as an external dedicated server, your IP will be of the host machine and the Port will be the one which you have set in your configuration file (by default this is 8211). Check out our [Server Configuration](palworld-configuration.md) guide for more information about the port.

## Direct Connect

Begin by launching Palworld from your game launcher. In the main menu, select **Join Multiplayer Game**.

![](https://github.com/zaphosting/docs/assets/42719082/fefc7ead-5098-4bdb-aa56-c9d78673d7e8)

Within the dedicated server browser, head over to the bottom of the page. Enter your IP and Port details into the bottom search box. Once ready, press the **Connect** button and you will join your server.

:::note
Ensure that you use the bottom search box, not the top. The top is used to search for servers by name in the server list.
:::

![](https://github.com/zaphosting/docs/assets/42719082/ae31ddee-8992-486a-aef3-e6e4d115f018)

If you cannot join the server successfully and receive a timeout error, please ensure that the inputted IP and Port is correct and that your server is online. You can use the console section of your webinterface for your Palworld server to help with debugging.