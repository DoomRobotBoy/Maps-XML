<?xml version="1.0"?>
<map proto="1.3.6">
<name>Glaciated Valley</name>
<version>1.0.0</version>
<objective>Be the first team to reach 600 points!</objective>
<authors>
    <author>rockymine</author>
</authors>
<contributors>
    <contributor contribution="XML">DoomRobotBoy</contributor>
</contributors>
<teams>
    <team color="dark red" max="20" overfill="22">Red Team</team>
    <team color="blue" max="20" overfill="22">Blue Team</team>
</teams>
<score>
    <limit>600</limit>
</score>
<kits>
    <kit name="spawn">
        <item slot="0" damage="-3000">stone sword</item>
        <item slot="1" damage="-3000" enchantment="arrow infinite:1">bow</item>
        <item slot="28">arrow</item>
        <item slot="3" amount="32">bread</item>
        <chestplate enchantment="protection projectile:1" damage="-3000">chainmail chestplate</chestplate>
        <boots enchantment="protection fall:1" damage="-3000">iron boots</boots>
        <potion duration="4">heal</potion>
        <potion duration="4" amplifier="10">damage resistance</potion>
    </kit>
    <kit name="red" parents="spawn">
        <helmet color="cd0000" damage="-3000">leather helmet</helmet>
    </kit>
    <kit name="blue" parents="spawn">
        <helmet color="0066cc" damage="-3000">leather helmet</helmet>
    </kit>
</kits>
<regions>
    <apply block="deny-all">
        <rectangle min="-oo,-oo" max="oo,oo"/>
    </apply>
</regions>
<spawns>
    <spawn team="red" kit="red" yaw="135">
        <cylinder base="-484.5,14,-319.5" radius="1"/>
    </spawn>
    <spawn team="blue" kit="blue" yaw="-135">
        <cylinder base="-588.5,14,-319.5" radius="1"/>
    </spawn>
    <default yaw="0">
        <cylinder base="-536.5,9,-356.5" radius="1"/>
    </default>
</spawns>
<king>
    <hills>
        <hill name="Lake Hill" capture-time="20s" ratio="1" neutral-state="true">
            <capture><cylinder base="-536.5,10,-372.5" radius="6" height="2"/></capture>
            <progress><cuboid min="-530,9,-366" max="-543,10,-379"/></progress>
            <captured><cuboid min="-530,9,-366" max="-543,10,-379"/></captured>
        </hill>
        <hill name="Glacier Hill" capture-time="15s" ratio="1.5">
            <capture><cylinder base="-536.5,5,-333.5" radius="5" height="2"/></capture>
            <progress><cuboid min="-531,3,-339" max="-542,4,-328"/></progress>
            <captured><cuboid min="-531,3,-339" max="-542,4,-328"/></captured>
        </hill>
        <hill name="Cave Hill" capture-time="15s" ratio="0.5">
            <capture><cylinder base="-536.5,12,-305.5" radius="2"/></capture>
            <progress><cuboid min="-534,11,-308" max="-539,11,303"/></progress>
            <captured><cuboid min="-534,11,-308" max="-539,11,303"/></captured>
        </hill>
    </hills>
</king>
<itemremove>
    <item>stone sword</item>
    <item>bow</item>
    <item>arrow</item>
    <item>leather helmet</item>
    <item>chainmail chestplate</item>
    <item>iron boots</item>
    <item>golden apple</item>
    <item>bread</item>
</itemremove>
<killreward>
    <item amount="1">golden apple</item>
</killreward>
</map>
