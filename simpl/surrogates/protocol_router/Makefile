#===============================================================
#
#  Makefile for surrogate/protocol_router tree
#
#-----------------------------------------------------------------------
#    Copyright (C) 2002, 2008 FCSoftware Inc. 
#
#    This library is free software; you can redistribute it and/or
#    modify it under the terms of the GNU Lesser General Public
#    License as published by the Free Software Foundation; either
#    version 2.1 of the License, or (at your option) any later version.
#
#    This library is distributed in the hope that it will be useful,
#    but WITHOUT ANY WARRANTY; without even the implied warranty of
#    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
#    Lesser General Public License for more details.
#
#    You should have received a copy of the GNU Lesser General Public
#    License along with this library; if not, write to the Free Software
#    Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA
#
#    If you discover a bug or add an enhancement please contact us at: 
#
#	SIMPL project mailing list
#-----------------------------------------------------------------------
#===============================================================
#$Log: Makefile,v $
#Revision 1.6  2009/04/14 20:58:14  bobfcsoft
#added i386 target
#
#Revision 1.5  2009/01/08 17:29:29  bobfcsoft
#more debian prep
#
#Revision 1.4  2008/12/02 14:16:58  bobfcsoft
#removed @
#
#Revision 1.3  2008/11/27 20:37:49  johnfcsoft
#clobber-->clean
#
#Revision 1.2  2008/11/26 17:29:19  bobfcsoft
#cleanup
#
#Revision 1.1.1.1  2005/03/27 11:50:58  paul_c
#Initial import
#
#Revision 1.1  2002/11/22 16:38:39  root
#Initial revision
#
#===============================================================


#
# NOTE: these are relative to the next lower subdirectory
#       and NOT to this level
#
SIMPL_BIN=../../../bin

PROJECT=SIMPL

SRC_DIR=src
TEST_DIR=test

#===================================
# entry point for simple make
#===================================
all:
	@echo "$(PROJECT) surrogate/protocol_router build <all> starting"
	@echo `date`
	make -C $(SRC_DIR) SIMPL_BIN=$(SIMPL_BIN)
	@echo "$(PROJECT) surrogate/protocol_router <all> done"
	@echo `date`

#===================================
# to force a total rebuild
#===================================
clean:
	@echo "$(PROJECT) surrogate/protocol_router <clean> starting"
	make -C $(SRC_DIR) -s clean
	@echo "$(PROJECT) surrogate/protocol_router <clean> done"

#===================================
# to move into master area
#===================================
install:
	@echo "$(PROJECT) surrogate/protocol_router build <install> starting"
	@echo `date`
	make -C $(SRC_DIR) install SIMPL_BIN=$(SIMPL_BIN)
	@echo "$(PROJECT) surrogate/protocol_router <install> done"
	@echo `date`

#========================
# remove from master area
#========================
uninstall:
	@echo "$(PROJECT) surrogate/protocol_router <uninstall> starting"
	@echo `date`
	make -C $(SRC_DIR) uninstall SIMPL_BIN=$(SIMPL_BIN)
	@echo "$(PROJECT) surrogate/protocol_router <uninstall> done"
	@echo `date`

i386:
	@echo "$(PROJECT) surrogate/protocol_router build <i386> starting"
	@echo `date`
	make -C $(SRC_DIR) i386 SIMPL_BIN=$(SIMPL_BIN)
	@echo "$(PROJECT) surrogate/protocol_router <i386> done"
	@echo `date`

